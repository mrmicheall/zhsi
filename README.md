# ZHSI Releases

This repo will be used to upload and keep track of ZHSI releases

Please see the Wiki (https://gitlab.com/sum1els737/zhsi-releases/wikis/ZHSI) for instructions

## Changelog

#### v1.17.1 (bugfix)

**162 Fixed:** Fix rings sometimes not shown, due to incorrect apt.dat parsing resulting in no lat/lon data for some airports.

#### v1.17.0

**143 Fixed:** Tuned VOR was not displayed correctly in PLN mode.  
**146 Added:** Position trend vector (turn) added to ND. Might need fine tuning  
**157 Fixed:** Hopefully this issue is now fixed (Lat deviation in PFD)  
**158 Added:** Fuel Flow used indication on Upper EICAS  
**161 Fixed:** Flap position in newer Zibo versions  
**163 Added:** CWS-R and CWS-P annunciations  
**166 Added:** Glideslope deviation to ND (APP mode)  
**164 Fixed:** Flightplan not shown right after loading .FMS flightplan  

##### Other Changes:

**Added: New feature** - Captain + FO Chronos  
Corrected spacing between 5/10 degree marks for the compass (PFD)  
Terrain Display should no longer show water (oceans)  

#### v1.16.0

**18 Added:** New feature, ISFD Instrument Added (Chronos to follow)  
**149 Fixed:** Lateral Deviation was inverted  
**144 Fixed:** LNAV path deviation superimposed with ILS localizer deviation  
**153 Added:** Option to enable UI to be minimized on startup  
**151 Tweaked:** Memory issue not allowing all panels to be displayed has been tweaked, but have a look at issue #151 for more details  
**156 Fixed:** PFD altitude to show a "negative" sign for altitudes below 0  

#### v1.15.1 (Bugfix)

**145 Fixed:** DU displays does not turn off or start in Cold and Dark state.

**Other:** new versioning format (Major.Minor.Revision)