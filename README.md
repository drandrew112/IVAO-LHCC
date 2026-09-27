# LHCC Sectorfile for IVAO Aurora
* Previous contributors (2022-24~): Janos V (327013), Keve K (492790)
* Current contributors (2025-26): Andras Hevesy (645592), Istvan E (338686)

Possible problems with LHBP.GTS.</br>
Sometimes Aurora can't load gate slots and sectorfile loading fails. You can press F1 and load the sectorfile again.</br>
Just IVAO software things:)

## Installation
1. Download the complete zip version from the Main Branch.
2. Extract directly (or copy) and _**OVERWRITE**_ to the SectorFiles folder within your Aurora Installation folder
    * **Windows:**\
      `<Aurora_Root_folder>\SectorFiles`\
      by default:\
      `C:\Aurora\SectorFiles`\
      Your other downloaded sectorfiles will remain intact.
3. Optional: Move the profile file (contains the tags) from Include/HU/PREFS folder to Aurora/Profiles

## Screenshots
### Budapest Ground Layer
![LHBP](img/lhbp.png "LHBP Ground Layer")
### Budapest TMA
![LHBP_TMA](img/lhbp_tma.png "LHBP TMA")
### Tags
It's in the profile file: LHBP_APP.cpr
#### Airborne traffic
![LHBP_TMA_TAGS](img/lhbp_tma_tags.png "LHBP TMA TAGS")
![TAGS_AIR_2](img/tags_air_2.png "LHBP Inbound traffic")
![SVW4015_TO_TWR](img/tags_outtransfer.png "SVW4015 transfer to tower")
#### Ground traffic
Details depends on SQK mode! Aircraft type and speed only available when sqk is on.
![LHBP_GND_1](img/tags_gnd_lhbp1.png "LHBP Ground traffic")