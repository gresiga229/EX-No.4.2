# EX No.4.2. CUT SECTION OF SOLIDS
## DATE:09/11/26

## AIM: 
To create the solid model from given drawing and section the solid model

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
### Step 1: Create the initial sketch

1. Open Fusion 360 and select the **Design → Solid** workspace.
2. Click **Create Sketch** and select the Front (XZ) plane.
3. <img width="216" height="171" alt="Screenshot 2026-11-11 204524 - Copy (2)" src="https://github.com/user-attachments/assets/0e7777ae-ee98-4f6b-bc47-69a372800e99" />

4. Choose **Sketch → Line** and draw a vertical construction line through the origin. This will act as the centre axis of the wine glass.
5. <img width="542" height="767" alt="Screenshot 2026-11-11 204541 - Copy (2)" src="https://github.com/user-attachments/assets/e1e1ad1d-e5c0-4d8d-b912-f1f7a9772ae8" />

6. Use the **Construction** option to convert the line into a construction line.
7. This centre line will be used as the axis for the Revolve operation.

### Step 2: Create the base profile

6. Choose **Sketch → Line** and start drawing the side profile of the circular base.
7. Draw a horizontal line from the centre axis towards the right side.
8. Set the base radius to 1.366 units, corresponding to an overall base diameter of 2.73 units.
9. Draw the slightly slanted upper and lower edges of the base.
10. Maintain the base thickness as shown in the sectional reference drawing.
11. Connect the lines to form a closed profile.

### Step 3: Create the stem profile

12. Continue the sketch from the inner edge of the base.
13. Use **Sketch → Line** to draw the vertical stem profile.
14. Maintain the stem length according to the dimension shown in the engineering drawing.
15. Set the stem thickness to 0.25 units.
16. Draw the opposite side of the stem profile and connect it to the base.
17. Ensure that the stem is symmetrical about the centre axis.

### Step 4: Create the bowl profile

18. Select **Sketch → Arc → 3-Point Arc** to create the curved outer profile of the bowl.
19. <img width="448" height="347" alt="Screenshot 2026-11-16 091632" src="https://github.com/user-attachments/assets/c8e19f2a-4431-45bc-b394-b4adf634b0b1" />

20. Start the arc from the upper end of the stem.
21. Draw the curved profile outward and upward to form the rounded bowl shape.
22. Use another arc to construct the inner wall of the bowl.
23. Maintain a uniform wall thickness of approximately 0.148 units as indicated in the sectional reference.
24. Connect the inner and outer profiles at the top to form the rim of the glass.
25. Use the **Dimension** tool to adjust the required radii and heights according to the sectional drawing.
26. <img width="562" height="513" alt="Screenshot 2026-11-11 204618" src="https://github.com/user-attachments/assets/9ab895b5-886c-4fe4-85dd-04461128c909" />

27. Connect all the sketch elements to form one continuous closed profile.
28. Click **Finish Sketch**.

### Step 5: Revolve the wine glass profile

27. Go to **Solid → Create → Revolve**.
28. Select the closed side-profile sketch as the profile.
29. Select the vertical construction line as the axis of revolution.
30. Set the angle to 360 degrees.
31. Select **New Body** as the operation.
32. Click **OK** to generate the complete three-dimensional wine glass.

### Step 6: Create the inner hollow portion

33. Select the top face of the bowl and click **Create Sketch**.
34. Choose **Sketch → Circle → Center Diameter Circle** if a circular opening needs to be constructed separately.
35. Use the **Extrude** command with the **Cut** operation to remove the required internal material, if the inner cavity was not already included in the revolved profile.
36. <img width="460" height="617" alt="Screenshot 2026-11-11 212828" src="https://github.com/user-attachments/assets/e079efe0-a637-4f20-afe9-8fc65b638782" />

37. Maintain the required wall thickness and bowl depth according to the sectional drawing.

### Step 7: Final inspection and drawing

37. Use the **Orbit** tool to inspect the completed wine glass from different directions.
38. Verify the overall height, base diameter and stem dimensions.
39. Check the bowl's outer and inner curved surfaces.
40. Ensure that the bowl is hollow and that the stem is properly connected to the base.
41. Save the completed 3D model.
42. Generate the front, top and side views along with the isometric view using the Drawing workspace.
43. Add the necessary dimensions, centre lines and hidden lines to complete the engineering drawing.
## INPUT:

![image](https://user-images.githubusercontent.com/113594316/199409656-c021c100-857a-4ae4-9752-9ae59465c9c2.png)

## OUTPUT:

<img width="992" height="707" alt="Screenshot 2026-11-15 190931" src="https://github.com/user-attachments/assets/461af987-04dd-458f-848e-ca116a462a75" />

## RESULT:
Thus, the cut section for solid model is created.


