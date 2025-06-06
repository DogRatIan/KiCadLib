# KiCad library and related files

## Setup
1) Clone all files to your harddisk. For example "U:\\_lib\\kicad", or "/opt/kicadlib".

2) At KiCad menu bar, select "Preferences->Configure Paths".

3) Add a new variable, name is "KICAD_DOGRATIAN", Value is "U:\\_lib\\kicad".
  ![ConfigurePaths.png](ConfigurePaths.png "Configure Paths")

4) Open Symbol Library Editor. At menu bar, select "Preferences->Manage Symbol Libraries".

5) Click the [Add existing library] button, then select the library file "00_DogRatIan.kicad_sym".
  ![ManageSymbolLibraries_symbol.png](ManageSymbolLibraries_symbol.png "Manage Symbol Libraries")

6) Open Footprint Library Editor. At menu bar, select "Preferences->Manage Symbol Libraries".

7) Click the [Add existing library] button, then select the library file "00_DogRatIan.pretty".
8) Click the [Add existing library] button, then select the library file "99_Bitmap.pretty".
  ![ManageSymbolLibraries.png](ManageSymbolLibraries_footprint.png "Manage Symbol Libraries")



## 0.15mm Design Rule
"blank_0_15mm_Rule.kicad_pcb" is a blank 50x50mm PCB file, with a 0.15mm design rule.

- Trace width: 0.15mm

- Trace routing grid: 0.15mm (5.9mil)

- Clearance: 0.145mm (5.7mil)

- Suggested routing grid: 0.15mm


![blank_0_15mm_Rule.png](blank_0_15mm_Rule.png "Manage Symbol Libraries")
