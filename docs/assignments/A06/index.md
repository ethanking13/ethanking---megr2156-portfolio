# A6 – [Bracket Drawing]

## Objective
For this assignment, I will generate a multi-view engineering drawing of the bracket that I designed for last week.

## Parametric Design

Before I could start modeling, I had to input all of the dimensions I calculated in the previous A5 assignment to make the design fully parametric. I rounded the values up slightly to account for stress and ensure the design would meet the required strength and safety requirements.

<img width="926" height="661" alt="Screenshot 2026-09-30 203913" src="https://github.com/user-attachments/assets/0e6e5a2a-3a2c-4486-ba01-a2995013db21" />

**[Figure 1: Equations]**

## CAD Model
For my modeling process I decided to follow the order of each figure and built upon one another. I used my dimensions that I solved for to make sure every value was correct. But due to some modeling mistakes I decided to start with Figure B then move into Figure A, then C,D,E to keep the orginal order.

<img width="806" height="727" alt="Screenshot 2026-09-30 210020" src="https://github.com/user-attachments/assets/84f0b9eb-1a77-46d0-a36f-dd665cf510cf" />

**[Figure 2: Figure B Model]**

<img width="712" height="755" alt="Screenshot 2026-09-30 205418" src="https://github.com/user-attachments/assets/dcc7bf11-15f4-4e3c-ab7a-3084cf4c0b4d" />

**[Figure 3:  Figure B Extrusion and Figure A model]**

<img width="1377" height="693" alt="Screenshot 2026-09-30 211515" src="https://github.com/user-attachments/assets/20e2e6ad-35b3-4ad2-b486-b6fedbddfebb" />

**[Figure 4: Figure A Extrusion]**

<img width="987" height="807" alt="Screenshot 2026-09-30 212619" src="https://github.com/user-attachments/assets/fde62d3e-2c09-420f-9e0a-f2bf650e9128" />

**[Figure 5: Figure C Model]**
<img width="1682" height="968" alt="Screenshot 2026-09-30 212646" src="https://github.com/user-attachments/assets/ca878036-62e4-4657-adec-0680746cb38b" />

**[Figure 6: Figure C Extrusion]**

<img width="1506" height="552" alt="Screenshot 2026-09-30 213041" src="https://github.com/user-attachments/assets/2f3898ef-7f89-4bc6-93d3-5f08dcc2d264" />

**[Figure 7: Figure D Model]**

<img width="745" height="873" alt="Screenshot 2026-09-30 213538" src="https://github.com/user-attachments/assets/db2753cf-ef22-495c-b726-1c06a9e9319f" />

**[Figure 8: Figure D Extruded/Mirrored]**

<img width="1052" height="736" alt="Screenshot 2026-09-30 213831" src="https://github.com/user-attachments/assets/c4c412ef-842c-484f-99d1-cfd608e25c5c" />

**[Figure 9: Figured E Model]**

<img width="1451" height="725" alt="Screenshot 2026-09-30 213948" src="https://github.com/user-attachments/assets/ce561cd8-3ebe-4e4c-8c3e-a779e7c3d9bb" />

**[Figure 10: Figure E Extruded/Mirrored]**

<img width="637" height="747" alt="Screenshot 2026-09-30 214134" src="https://github.com/user-attachments/assets/f4dfcfdf-e136-4400-a999-0960fa0e2e23" />

**[Figure 11: Complete Part]**

<img width="1452" height="750" alt="Screenshot 2026-09-30 214639" src="https://github.com/user-attachments/assets/3de7a9e6-f6ec-4176-a263-297d622bcd49" />

**[Figure 12: 6061-T6 Alumnium Material]**


## Drawing
For my drawing I used ***ANSI A*** Version and projected my model in a 3d angle format
<img width="690" height="198" alt="Screenshot 2026-09-30 220325" src="https://github.com/user-attachments/assets/2ba2d9be-b554-4089-a5e1-526f58a77ac4" />

**[Figure 13: Drawing Information]**

I then placed the views of my model on the page so people can see the model from every angle
<img width="1071" height="826" alt="Screenshot 2026-09-30 220300" src="https://github.com/user-attachments/assets/223a8e0d-566f-4db3-857c-a2c432c5dba2" />

**[Figure 14: Model Views]**

I then added the dimensions in. I made sure to include every important dimension and tolerance so that anyone who comes across this drawing is able to perfectly replicate the model without having to ask the designer (Me) questions.

<img width="1068" height="822" alt="Screenshot 2026-09-30 235643" src="https://github.com/user-attachments/assets/53bd4655-a2cf-405e-b42e-60f8eda3043e" />


**[Figure 15: Dimensions and Tolerances]**

## Projection Information
I was unable to get the proper symbols to show up that represent the 3rd angle view but I was able to screenshot the drawing properties to prove it was the third angle.

<img width="707" height="677" alt="Screenshot 2026-09-30 233716" src="https://github.com/user-attachments/assets/9eddd8ce-e432-4b2c-804d-0884b3e2ba82" />

**[Figure 16]**

## Reflections 

### A.

For my parametric model, I used a stiffness equation to determine the required dimension for Figure A, which controlled the diameter of the feature. The equation I used was:

$$
d_a = \sqrt[4]{\frac{64PL^3}{3\pi E\delta}}
$$

I first used this analytical equation to calculate the required dimension based on the applied load, beam length, material modulus, and allowable deflection. After solving the equation, I entered the calculated dimension into the **Equations** section of SolidWorks so that the dimension was incorporated into my parametric model. The analytical equation itself was not entered directly into SolidWorks; instead, the solved dimension was used as the value controlling the specified feature.

The calculated dimension did not change later in the assignment, so no additional manual rework was required and the rest of the model remained unchanged. This process helped me understand how engineering calculations can be used to determine CAD dimensions and how those dimensions can then be incorporated into a parametric model.

### B. 

For my drawing, I applied a tighter tolerance of −0.001 in to Figure C because this feature requires a controlled fit and the previous assignment specified that a minimum amount of play was desired. The tighter tolerance helps maintain the intended fit between the mating components by limiting variation in the feature. I applied a looser tolerance of −0.0005 in to Datum B because this feature needs enough clearance to allow the components to slide relative to each other. Using a looser tolerance for this feature allows for easier movement while still maintaining the required function of the design. The tolerance classes were selected based on the functional requirements of each feature rather than applying the same tolerance to every dimension. This approach also avoids unnecessarily tight tolerances on features where additional precision would not improve the function of the part.

### Time Spent and Lessons Learned

I spent approximately 5 hours completing this assignment. The assignment did not require as much modeling time because most of the design work had already been completed in Assignment 5, so the primary task was organizing and combining the completed work into the final design and drawing. One of the main skills I learned from this assignment was how to use the **SolidWorks Drawing** feature. I was previously more familiar with creating drawings in **Creo Parametric**, so adapting to the SolidWorks drawing environment required some additional time. Learning how to create and organize the drawing in SolidWorks gave me experience working with a different CAD documentation system and helped me better understand how engineering drawings are produced from a completed parametric model.


### Model and Drawing
<a href="../../images/a6model.SLDPRT" download>CAD Model</a>

<a href="../../images/a6modeldraw.SLDDRW" download>CAD Drawing</a>
