# Editable payload cases

Start with [1 kg](1kg/study.FCStd). The [2 kg](2kg/study.FCStd), [4 kg](4kg/study.FCStd) and [8 kg](8kg/study.FCStd) projects use the same upper-arm plate, held pose, material, supports, mesh and non-payload loads. Each file embeds the geometry, native FEM setup, mesh and saved results. No external geometry file, custom launcher or add-on workbench is needed.

The original study used **FreeCAD 1.1.4** (Windows x86-64/Python 3.11) and **CalculiX 2.22**. Gmsh 4.15.0 is needed only if remeshing. Versions and executable checksums are in [dependencies.json](metadata/dependencies.json). Software binaries are not included.

## Open and inspect

1. Open `1kg/study.FCStd`, switch to **FEM**, and expand `Analysis`. Double-click the analysis group if it needs activation.
2. Inspect `Al6061`, `RootFixed`, `AllocatedLinkWeight`, the eight `DeadForce` and eight `PayloadForce` objects, `Mesh`, and `Solver`. Values and face/edge references are in the **Data** tab. Labels retain the original values after edits; use the actual properties when checking a change.
3. Double-click `CCX_Results` to inspect the saved result, or use `Pipeline_CCX_Results` for field visualization. The 50 mm reference cube and direction lines are not meshed.

## Copy and rerun

1. Use **File > Save As** to make a working copy outside this checkout.
2. Double-click `Solver` (**CalculiX 2.22 | linear static | rerun here**). Choose a new writable **Working Directory** with the `...` button, such as a `solver` folder beside your working copy. The source machine's saved directory was cleared in these copies. Set an explicit, separate directory for each case; also check any global FEM working-directory preference.
3. If required, point **Edit > Preferences > FEM > CalculiX** to your installed `ccx.exe`.
4. Keep the saved mesh and loads unchanged to reproduce the comparison. Click **Write .inp File**, then **Run CalculiX**. Wait for result import, close the solver task panel, inspect the new results and save your copy.

A message that a single material's shape reference is ignored is expected: the sole material applies to the whole upper-plate FEM mesh.

## Try changing a load

On a separate 1 kg copy, double-click **Dead bolt 01** (`DeadForce01`, `UpperPlate:Face12`). Change **Force** from 28.004587 N to **56 N**, keep `DeadDirection01:Edge1`, and click **OK**. Rerun using a separate working directory as above and compare with the saved 1 kg result. This changes a non-payload force. To investigate a different payload, scale all eight payload-force magnitudes consistently while retaining their directions; the plate's payload-mass property is provenance and does not drive those forces automatically.

## Setup and results

| Payload | Peak von Mises | Maximum plate displacement |
|---|---:|---:|
| 1 kg | 14.448 MPa | 0.4288 mm |
| 2 kg | 19.257 MPa | 0.5715 mm |
| 4 kg | 28.875 MPa | 0.8570 mm |
| 8 kg | 48.111 MPa | 1.4280 mm |

Each case includes its original `setup.json`, `audit.json` and `metrics.json`. The accepted shared mesh has 151,623 nodes and 90,506 curved C3D10 elements, with nominal h=2.5 mm. Material is 6061 aluminum with specified minimum yield 240 MPa; the original screens were 120 MPa stress and 1 mm isolated-plate displacement. [Mesh comparisons](metadata/comparison.json) retain the refinement checks and interpretation. The 1 mm plate criterion crosses near 5.001 kg; separate grip and wrist budgets in the original assessment cross earlier. This is a plate model, not an assembled-arm payload rating.

[Original reopen/rerun evidence](metadata/reopened-reruns.json) records identical saved and rerun fields for all four original projects. Its project checksums refer to the originals before clearing the saved working directory; [provenance](../PROVENANCE.md) maps both versions. This curation checked archive integrity and unchanged engineering data without opening FreeCAD or performing a new solver/GUI run. Input decks and large raw solver outputs are regenerated from the embedded setup and are omitted here.
