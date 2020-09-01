# Mercbus-a320-neo

Mercs Livery for Airbus a320 Neo in MSFS2020

## Install:

1. Download ZIP from Releases
2. If you have other liveries installed, add Texture folder to `Community\liveries-a320\SimObjects\Airplanes\Asobo_A320_NEO`
3. Add the following to Aircraft.cfg

   [FLTSIM.*REPLACE WITH NEXT NUMBER*]  
   title = "Mercbus A320 Neo" ; Variation name  
   model = "" ; model folder  
   panel = "" ; panel folder  
   sound = "" ; sound folder  
   texture = "MERCS" ; texture folder  
   kb_checklists = "Boeing747-400_check" ; Procedures/Checklist sibling file name  
   kb_reference = "Boeing747-400_ref" ; Reference information sibling file name  
   description = "TT:AIRCRAFT.DESCRIPTION" ; Variation description.  
   wip_indicator = 0 ; know if the variation is good to go or still WIP : -1=Disabled, 0=Rough, 1=1st Pass, 2=Finished  
   ui_manufacturer = "TT:AIRCRAFT.UI_MANUFACTURER" ; e.g. Boeing, Cessna  
   ui_type = "MERCS" ; e.g. 747-400, 172  
   ui_variation = "MERCS" ; e.g. World Air, IFR Panel  
   ui_typerole = "Commercial Airliner" ; e.g. Single Engine Prop, Twin Engine Prop, Rotorcraft, etc  
   ui_createdby = "Mercs Clan" ; e.g. Asobo Studio, Microsoft, FSAddonCompany, etc  
   ui_thumbnailfile = "" ; app relative path to ThumbNail image file  
   ui_certified_ceiling = 39800 ; service ceiling / max certified operating altitude (ft)  
   ui_max_range = 3500 ; max distance the aircraft can fly between take-off and landing in (NM)  
   ui_autonomy = 7 ; max duration the aircraft can fly between take-off and landing in (Hrs)  
   ui_fuel_burn_rate = 5300 ; average fuel consumption per hour (lbs/hr) - reminder: fuel density is ~6.7lbs per US gallon  
   atc_id = "xmerc" ; tail number  
   atc_id_enable = 0 ; enable tail number  
   atc_airline = "MERC" ; airline name
   atc_flight_number = "1" ; flight number  
   atc_heavy = 1 ; heavy?  
   atc_parking_types = "GATE,RAMP,CARGO" ; "ANY" / "RAMP" / "CARGO" / "MIL_CARGO" / "MIL_COMBAT" / "GATE" / "DOCK"  
   atc_parking_codes = "" ; Comma separated and may be as small as one character each  
   atc_id_color = "#fffff" ; color for the tail number : i.e. "#ffff00ff"  
   atc_id_font = "" ; font for the tail number  
   isAirTraffic = 0 ; Is the plane usable for air traffic  
   isUserSelectable = 1 ; Is the plane selectable by the use

4. Add the following to Layout.json  
   `{ "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_ENGINES_ALBD.PNG.DDS", "size": 2796344, "date": 132398508758630094 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_ENGINES_ALBD.PNG.DDS.json", "size": 102, "date": 132398508758580090 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_FUSELAGE_ALBD.PNG.DDS", "size": 2796344, "date": 132398508745550481 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_FUSELAGE_ALBD.PNG.DDS.json", "size": 102, "date": 132398508745510484 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_WINGS_ALBD.PNG.DDS", "size": 2796344, "date": 132398508751510304 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_WINGS_ALBD.PNG.DDS.json", "size": 102, "date": 132398508751470306 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_LIVERY_ALBD.PNG.DDS", "size": 5592560, "date": 132398507575965146 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_LIVERY_ALBD.PNG.DDS.json", "size": 119, "date": 132398507575895148 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_LIVERY_TEXTS_ALBD.PNG.DDS", "size": 5592560, "date": 132398507200106298 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/A320NEO_AIRFRAME_LIVERY_TEXTS_ALBD.PNG.DDS.json", "size": 119, "date": 132398507200036293 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/texture.CFG", "size": 166, "date": 132243417610000000 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/thumbnail.JPG", "size": 236335, "date": 132200099790000000 }, { "path": "SimObjects/Airplanes/Asobo_A320_NEO/TEXTURE.MERCS/thumbnail_small.JPG", "size": 33608, "date": 132270122080000000 }`
