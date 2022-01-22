# CustomInsoles

Workflow:

1. Scanned both feet with ScandyPro on Iphone 13
2. Imported scans from Iphone to PC (A), then into meshmixer for cleanup, make solid(B). Only concerned about surface that contacts ground.  Export as stl.
A. Raw Hollow Scan ![alt text](https://github.com/scharpham/Personalprojects/blob/main/Insoleproject/RawScan.PNG)
B. Scan cleaned/made solid(Underside) ![alt text](https://github.com/scharpham/CustomInsoles/blob/main/SolidUnderside.PNG)


3. Reimport edited to meshmixer,  alter oreintation, position etc(may have to iterate this step, unlikely to get it correct first attempt.)
C . Scan cleaned/made solid(Topside) ![alt text](https://github.com/scharpham/CustomInsoles/blob/main/Solidtopside.PNG)
3. Export Stl from Meshmixer to local machine. 
4. Trace each foot onto paper, take measurements in mm.
5. In the Gensole website http://gensole.com/, not my website, credit to "gyrobot" recreate foot pattern for the base of the insole based on measurements
6. Import stl of foot scan(positive form) into gensole. 
7. Position foot scan with what you determine to be the correct orientation/placement on top of insole.
8. Use the "Solemorph" function to subtract the foot stl from the insole, to create the custom insole, iterate measurements as needed.
D.  Gensole view ![alt text](https://github.com/scharpham/CustomInsoles/blob/main/Gensole.PNG)
9. Save as zip. You can later import the zip file back into the webapp, if you want to make adjustment based on your future fit.
10. Zip file will contain stl of insole. Find this. You may be able to use as-is, but my insoles are just a bit too large to fit on my print area(prusa mk3s)
11. Import stl into fusion, cut down insole length. I cut to 200 mm from heel, your measure measurements will vary.
E. ![alt text](https://github.com/scharpham/CustomInsoles/blob/main/FusionChoppedTopView.PNG)
F. ![alt text](https://github.com/scharpham/CustomInsoles/blob/main/FusionChopped.PNG)
12. Export stl from fusion, import into prusaslicer.
13. Prusaslicer settings, TPU filament, Gyroid infill, 25%. Print slow 20mm/s, 15mm/s bridges. Slice and print.
G. ![alt text](https://github.com/scharpham/CustomInsoles/blob/main/Prusaslicer(10%25)view.PNG)
14. Iterate steps 3-13 to find what works for you. 
