Pirate Kit models for the game (Kenney Pirate Kit 2.1, CC0) — 72 files named pk_*.glb
================================================================================
These are the original GLB files with ONE change: the colour texture (colormap.png) is now embedded inside every file.
(The originals point to Textures/colormap.png next to the file; uploaded as they are, the models would show up grey.)

UPLOAD
 1. Open the GitHub repo that is behind MODEL_BASE_URL  (CONFIG > MODEL_BASE_URL, e.g. .../cs-quest-models).
 2. Drag ALL pk_*.glb files into the SAME folder where the other game models are (the folder that already holds hk_*.glb / gy_*.glb / furn_*.glb).
    Do not create a sub-folder: the game asks for  <MODEL_BASE_URL>/pk_<name>.glb
 3. Commit. GitHub Pages needs a minute or two to publish.
 4. In the CONFIG tab set MODEL_VERSION to a new value (e.g. pk1) so browsers drop their cached models.
 5. In Apps Script run pirateIslandCheck() — it fetches 4 of the files and prints HTTP 200 + size when the upload worked.

The license file (Kenney_PirateKit_License.txt) can go in the repo too (credit to Kenney is optional).
Only a part of the 72 files is used by the island theme (about 38); the rest are there for shop items later.
