Halloween 2026 model files (Kenney Graveyard Kit, CC0 — credit voluntary: kenney.nl)
Upload every hw_*.glb in this folder to the root of the models repo (the same place as xmas_*.glb), then:
  1. Paste the new Gamify.gs and RoomEngine.html (New version).
  2. Optional: set CONFIG MODEL_VERSION to a new value (e.g. hw1) so browsers fetch the new files.
  3. Run addHalloweenItems() ONCE in the Apps Script editor (adds the HW_1-4 spots, ~69 items, 3 badges, extends the Halloween lighting preset to 2026-11-02).
The texture is embedded in RoomEngine.html and the files have no texture reference, so there is no colormap.png request.
