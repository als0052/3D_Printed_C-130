# 1. README for 3D Print C-130
-----
* Created by als0052
* Created on 03-30-2021
* Updated on 03-30-2021
-----

# 2. TODO Items
* Add print settings later once successful prints are made

# 3. Original C-130 Model:
Author: [Shyam Murali](https://grabcad.com/library/iaf-lockheed-martin-c-130j-super-hercules-1)

Appears to be C-130J Extended Forward Fuselage

# 4. Objective
Modification to a Solid Works C-130H or C-130J 3D model for 3D printing with either PLA or PETG on a Prusa i3 Mk3s. 

# 5. Modifications
These files will use a form of the British small arms numbering system. Small changes are indicated by the addition of an asterisk ('star', *) to the Mk ('Mark') number. The numbering will be done in roman numerals

## 5.1 Current Modification Versions
* Mk IV
  - First modification attempt
* Mk V
  - All parts designed to fit together with 3D printed 'keys'
  - No model scaling in Solid Works. Model is scaled in the slicer
  - Separate parts are created by cutting the original model at strategic locations
  - The parts are converted to .stl files and then sliced using PrusaSlicer2 or Simplify 3D
* Mk V*
  - Small modifications to the Mk V design
* Mk VI
  - Complete re-work of the Mk V design
  - Uses combination of 3D printed 'keys' and metal fasteners
  - Re-work started after realization that printing the empennage in one piece is not going to work out without soluble support
  - Model is scaled in SolidWorks to 25% the original size from Shyam's 3D model
      - If a different scale is needed the 3D model will have to be significantly re-worked in SolidWorks
* Mk VI*
  - Minor changes to the Mk VI design
  - Does away with the M3 screws between the Forward-Center Fuselage boundary to affix the Wing Center Box to the Center Fuselage. 
  - Instead screws will be mounted vertically to affix the Wing Center Box to the Center Fuselage

## 5.2 Other C-130 Models on GrabCad:
* [Non-SolidWorks](https://grabcad.com/library/lockheed-c-130-1)
* [Non-SolidWorks](https://grabcad.com/library/hercules-c-130-2)
* [SolidWorks](https://grabcad.com/library/c-130-1)

# 6. Files and Directory Structure
```raw:
3d_print_c130/
  README.md
  iaf-lockheed-martin-c-130j-super-hercules-1.snapshot.7/
    Cutup Model/
      Mk VI/
      Mk VIstar/
      Mk IV.zip/                 // Archived
      Mk V.zip/                  // Archived
      Mk Vstar.zip/              // Archived
    S3D/                         // Simplify 3D factory files, support files, G-code files, etc.
      Old Settings/              // Non-current Simplify 3D files
    C-130 No Markings.zip        // Original 3D model without the markings and surface details
    C-130.zip                    // Backup copy of the original model
  c-130-hercules.snapshot.1.zip  // Different model that didn't workout. Made by different author.
```