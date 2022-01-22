# CustomInsoles

Workflow:

1. Scanned both feet with ScandyPro on Iphone 13
2. Imported scans from Iphone to PC, then into meshmixer for cleanup, make solid. Export as stl.
![alt text](https://github.com/scharpham/Personalprojects/blob/main/Insoleproject/RawScan.PNG)
3. Reimport edited to meshmixer,  alter oreintation, position etc(may have to iterate this step, unlikely to get it correct first attempt.)
3. Export Stl from Meshmixer to local machine. 
4. Trace each foot onto paper, take measurements in mm.
5. in the Gensole website http://86.19.71.184:4445/ , recreate foot pattern for the base of the insole based on measurements
6. Import stl of foot scan(positive form) into gensole. 
7. Position foot scan with what you determine to be the correct orientation/placement on top of insole.
8. Use the "Solemorph" function to subtract the foot stl from the insole, to create the custom insole, iterate measurements as needed.
9. Save as zip. You can later import the zip file back into the webapp, if you want to make adjustment based on your future fit.
10. Zip file will contain stl of insole. Find this. You may be able to use as-is, but my insoles are just a bit too large to fit on my print area(prusa mk3s)
11. Import stl into fusion, cut down insole length. I cut to 200 mm from heel, your measure measurements will vary.
12. Export stl from fusion, import into prusaslicer.
13. Prusaslicer settings, TPU filament, Gyroid infill, 25%. Print slow 20mm/s, 15mm/s bridges. Slice and print.
14. Iterate steps 3-13 to find what works for you. 
