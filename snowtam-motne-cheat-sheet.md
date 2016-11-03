<# SNOWTAM & MOTNE Cheat sheet

### SNOWTAM
Runways are listed with their lowest numbered threshold. This means that for example reports for RWY29 are to be interpreted from reading RWY11's report, reading RWY thirds backwards.

* A) Aerodrome
* B) Time of issuing: MMDDHHmm (UTC)
* C) Runways for this report
* D) Cleared RWY length (if less than published)
* E) Cleared RWY width (if less than published)
* F) Deposits for each third  
	Listing represents layers from top to bottom, e.g. 67 represents Slush on top of ice
	* 1 = Damp
 	* 2 = Wet or water patches
 	* 3 = Rime or frost (<1 mm)
 	* 4 = Dry snow
 	* 5 = Wet snow
 	* 6 = Slush
 	* 7 = Ice
 	* 8 = Compact or rolled snow
 	* 9 = Frozen ruts or ridges
 	* NIL = Clear and dry
* G) Average depth in mm for each third
* H) Measured/Estimated friction  
If measured: two digits  
If estimated: one digit
9 = Unreliable
If friction was measured, the type of equipment is specified (e.g. GRT for grip tester or RFT for runway friction tester)  
* J) Critical snowbanks, listed in form H/DS:
	* H = height [cm]
	* D = distance from edge [m]
	* S = Side, can be L, R or LR
* K) RWY lights, if obscured. Followed by L, R or LR
* M) Expected time of further clearance to be completed
* N) Associated TWY conditions, not divided into thirds
* T) Clear text

### MOTNE
8 Digits appended to METAR: *AABCDDEE*

* AA: RWY designator
	* For parallel runways, R is designated by adding 50: 11L=11, 11R=61
	* 88 = All RWY
	* 99 = Prior RWY report repeated
* B: Type
 	* 0 = Clear and Dry
 	* 1 = Damp
 	* 2 = Wet or water patches
 	* 3 = Rime or frost (<1 mm)
 	* 4 = Dry snow
 	* 5 = Wet snow
 	* 6 = Slush
 	* 7 = Ice
 	* 8 = Compact or rolled snow
 	* 9 = Frozen ruts or ridges
 	* / = Not reported
* C: Extent
	* 1 = ≤ 10% covered
	* 2 = 11% to 25% covered
	* 5 = 26% to 50% covered
	* 9 = 51% to 100% covered
	* / = Not reported
* DD: Depth
	* 00 = < 1 mm
	* 01 - 90 = depth in mm
	* 92 = 10 cm
	* 93 = 15 cm
	* 94 = 20 cm
	* 95 = 25 cm
	* 96 = 30 cm
	* 97 = 35 cm
	* 98 = 40 cm
	* 99 = Not reported: **RWY not operational**
	* // = Not significant or measurable
* EE: Braking condition  
	01 - 90 = **Friction Coefficient** multiplied by 100: e.g. 05 = 0.05  
	91 - 95 = **Braking action** :
	* 91 = Poor
	* 92 = Medium/Poor
	* 93 = Medium
	* 94 = Medium/Good
	* 95 = Good
	
	99 = Unreliable  
	// = Not reported: **RWY not operational**
	
### Contamination definitions
As defined by ICAO

* Damp: the surface shows a change of colour due to moisture
* Wet: the surface is soaked but there is no standing water 
* Water patches: significant patches of standing water are visible
* Flooded: extensive standing water is visible
* Dry snow: Snow which can be blown if loose or, if compacted by hand, will fall apart again upon release
* Compacted snow: Snow which has been compressed into a solid mass that resists further compression and will hold together or break up into lumps if picked up
* Wet snow: Snow which, if compacted by hand, will stick together and tend to or form a snowball
* Slush: Water-saturated snow which with a heel-and-toe slap- down motion against the ground will be displaced with a splatter


### About
Source: <https://github.com/sebastiant/snowtam-motne-cheat-sheet>  
Revision: 2  
Disclaimer: This document comes with zero guarantees on validity. The information should not be used in aviation, unless confirmed to be correct by authorities and operation manuals. In no event shall the author be held liable for any damages caused by usage of this document. Have a great day!
