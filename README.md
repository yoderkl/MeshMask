# MeshMask
Use Autodesk Meshmixer to Generate Custom Facemasks [COVID-19 RESPONSE EFFORT]

MeshMask [v1.0] - README


--  THIS SOFTWARE SHOULD ALWAYS BE FREE TO USE AND DOWNLOAD                                  --
--  THIS SOFTWARE WAS CREATED DURING A GLOBAL PANDEMIC IN AN ATTEMPT TO HELP THOSE IN NEED.  --
--  THIS SOFTWARE IS NOT INTENDED FOR CLINICAL USE.                                          --
--  THIS SOFTWARE HAS NOT BEEN RIGOROUSLY TESTED.                                            --
--  THIS SOFTWARE IS NOT APPROVED BY THE FDA.                                                --
--  USE AT YOUR OWN MEDICAL-LEGAL RISK.                                                      --

Author:		Kevin Yoder, DDS

Contact:	DrYoder@CSofDentistry.com  (https://www.youtube.com/c/ComputerScienceofDentistry)

Date:		3/23/2020

Download:	link
Description:	A shortage of proper fitting and proper grade masks is negatively impacting the healthcare community during this time.
			  This software takes a 3D scan of a face as input, and will generate a sealed, custom-fit facemask that can be 3D printed.
			  This output of the Custom Facemask tool is intended to be a base for further development or modification.  I have included
			  one example that will attach respiration filters to the mask (filter created by http://copper3d.com/hackthepandemic/), so
			  others can get idea of what to do from there.  Please contact me if you would like me to develop this further.  Please share
			  this software with anyone and everyone you can think of that may be able to use it.

Requirements:
1. Meshmixer 3.5 (http://www.meshmixer.com/download.html)
2. Windows (64-bit) 				
3. Visual C++ Runtime Libraries  (https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads)
				                 (https://aka.ms/vs/16/release/vc_redist.x64.exe)
4. All File Contents:
			-MeshMask.exe
			-------------/parts/hook.obj
			-------------/parts/nanohackMaskAttachment.obj
			-------------/parts/nanohackMaskAttachment_cap.obj
			-------------/parts/nanohackMaskAttachment_cylinderForBoolean.obj
			-------------/parts/nanohackMaskAttachment_honeyCombCircle.obj
			-------------/img/mmImg.gif
			-------------/img/d3_ico.gif
			-------------/img/d3.ico


Instructions for use:

1.  Open Meshmixer
2.  Open Meshmask
3.  Import 3D face scan into Meshmixer  
4.  Click on "Custom Facemask" in the upper "Menu" section of Meshmask
5.  Follow the instructions in the middle "Menu Options" section of Meshmask
6.  After the mask is generated, you can add as many hooks/tabs as you need by pressing the "Add Hook/Tab" button
7.  To add the Nanohack Resipiration Filter(s) to the mask, click on the "+ Nanohack Respiration Filter" in the upper "Menu" section of Meshmask.
8.  Follow the instructions in the middle "Menu Options" section of Meshmask until Nanohack Filter is attached.  
9.  DOUBLE CHECK EVERYTHING BEFORE 3D PRINTING
10. DOUBLE CHECK EVERYTHING BEFORE POTENTIALLY USING
