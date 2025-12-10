---
layout: project
title: MAE 3270 Final Project
description: Final Design Project for MAE3270
technologies: [Autodesk Fusion, ANSYS Material]
image: /assets/images/3270-q3.png
---

5.2.1 - Results
1:

![CAD model of torque wrench]({{ "/assets/images/3270-q1.png" | relative_url }}){: .inline-image-r style="width: 500px"}

2:

For our design we used Titanium alloy Ti-6AI-4V because it has a really great combination of high strength, low density, and corrosion resistance which is great for demanding and high performance applications. It has a tensile strength of about 130,000 psi, meaning it is capable of withstanding substantial mechanical loads without permanent deformation. Also, its low density relative to steel enables meaningful weight reduction while maintaining structural integrity, which results in a lighter and more durable component that helps have both usability and effectiveness. 

3:

![Model of Loads and boundary conditions]({{ "/assets/images/3270-q3.png" | relative_url }}){: .inline-image-r style="width: 500px"}

The drive end of the design was sent constant by setting the displacement components to 0 so therefore it wouldn’t move. Then there was an applied 50 lbf = Torque/Length at the end face in the y-direction. 

4:

![Normal Strain Contours]({{ "/assets/images/3270-q4.png" | relative_url }}){: .inline-image-r style="width: 500px"}

5:

![Maximum Principal Stresses]({{ "/assets/images/3270-q5.png" | relative_url }}){: .inline-image-r style="width: 500px"}

6:

![FEM Calculations]({{ "/assets/images/3270-q6.png" | relative_url }}){: .inline-image-r style="width: 500px"}

Our maximum normal stress reaches about 55,052 psi, and the maximum deflection at load point is about 0.265 inches. At the strain gauge location, the FEM predicted a stress of about 1180.1 microstrain, and for titanium alloy Ti-6A1-4V is about 19,480 psi, which is close to the matlab estimate of about 1030.9 microstrain which is about 17,027.4 psi. 

7:

![Torque Wrench Sensitivity]({{ "/assets/images/3270-q7.png" | relative_url }}){: .inline-image-r style="width: 500px"}

8:
Cross-area is 0.4 by 0.25 for where the strain gauge will be put. 

Strain gauge selected: SGD-2/350-LY11

Normal resistance: 350 omega
Gauge Factor: 2
Active grid length: 0.118 inches
Active grid width: 0.098 inches
Matrix length: 0.299 inches
Matrix width: 0.228 inches
