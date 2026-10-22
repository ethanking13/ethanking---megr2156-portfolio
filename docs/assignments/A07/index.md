# A7 – FEA on a Bracket

## Objectives

- Design a component that is high-stiffness, high-strength, and lightweight.
-  Use Finite Element Analysis (FEA) to guide design decisions throughout the design process.
- Achieve mesh convergence within a 7% difference for stress, displacement, and safety factor results by adjusting the number of elements.
- Perform mesh convergence analysis before each geometric modification.
- If convergence is not achieved after three attempts, use the stiffness and stress results from the finer mesh and proceed with the finest mesh size.


## Initial Design
I will be using the same bracket from my previous assignment. I double checked the file to make sure everything was correct and ready for simulation. As you can see in the top left my selected material is 6061 Aluminum. 
<img width="1452" height="750" alt="Screenshot 2026-09-30 214639" src="https://github.com/user-attachments/assets/20d678b8-e652-4d47-825d-8e25b2b45257" />

## Simulation 1
For this first design I wont be changing anything. And here are my initial variables.
<img width="926" height="661" alt="Screenshot 2026-09-30 203913" src="https://github.com/user-attachments/assets/72d7afe8-5f27-4b16-9275-24c2364674e9" />

## Adding Proper Parameters
First I added a fixed geometry to the top flange of the bracket, This simulates the area that will slide against something and simulate the load.
<img width="957" height="665" alt="Screenshot 2026-10-21 202254" src="https://github.com/user-attachments/assets/728dd654-73e4-451f-b364-8fce4e1f4337" />

I next added a downward force of 400lbf. To simulate something pulling down on the end. In my calculations P=F/2 so 200. But to account for any error I just reverted back to my original 400lbf which if I was wrong it would workout because I am simulating a higher force which works out in the end.
<img width="1377" height="737" alt="image" src="https://github.com/user-attachments/assets/17d5e2e0-4dc9-4d89-a24b-f3e6e891920e" />

## Meshing
Next I was to choose the mesh quality and change it as I went on. I decided to go with the default mesh quality that's set in the middle for this first attempt. For each of the image below the pictures data follows. Stress, Displacement, and then Factor of Safety (FOS).

# Design 1 
For each simulation I ran it 3 different times. With different mesh values which gradually got finer and finer. Below you can see the "Mesh Control Bar" First Simulation was all the way to the left then second was directly in the middle, Then the 3rd and final run was on the far right
<img width="272" height="660" alt="Screenshot 2026-10-21 205624" src="https://github.com/user-attachments/assets/807b9531-47d5-4d46-89c9-8f510635ccf5" />


## Simulation 1-1
<img width="1557" height="737" alt="Screenshot 2026-10-21 233723" src="https://github.com/user-attachments/assets/cf0178ac-6d63-44ae-83bb-8967bfe25f95" />
<img width="1498" height="710" alt="Screenshot 2026-10-21 233736" src="https://github.com/user-attachments/assets/103c7bd6-72d2-4a11-93f7-200b2f824084" />
<img width="1522" height="741" alt="Screenshot 2026-10-21 233748" src="https://github.com/user-attachments/assets/0575e784-1e6c-47ec-a051-f8d299c75ef8" />

## Simulation 2-1
<img width="1550" height="695" alt="Screenshot 2026-10-21 233851" src="https://github.com/user-attachments/assets/f9d05af5-325d-4fef-b451-8426d53e18b4" />
<img width="1521" height="727" alt="Screenshot 2026-10-21 233903" src="https://github.com/user-attachments/assets/0ea37ed6-ad0c-4cb9-b6c7-6413a85a5a9c" />
<img width="1568" height="722" alt="Screenshot 2026-10-21 233911" src="https://github.com/user-attachments/assets/e22e24ed-c85f-48d1-b651-81635229de26" />

## Simulation 3-1
<img width="1547" height="717" alt="Screenshot 2026-10-21 234009" src="https://github.com/user-attachments/assets/85c88e8e-ce83-4125-a62c-e8721c156f86" />
<img width="1515" height="751" alt="Screenshot 2026-10-21 234027" src="https://github.com/user-attachments/assets/ef81aff6-d8cf-4de8-af04-5362c14f15fd" />
<img width="1517" height="707" alt="Screenshot 2026-10-21 234049" src="https://github.com/user-attachments/assets/41939889-8e64-431c-b7dd-6b9ab68bea13" />

### Discussion/Changes
Relatively my design held up pretty well in all the simulations. My only concern would be the part that connects the shaft and the connecting plate together. So I decided to add some support to that connecting flange.

## Design 2
<img width="702" height="722" alt="Screenshot 2026-10-21 235219" src="https://github.com/user-attachments/assets/79430776-239e-4e0d-be67-ab8e1b0e1552" />

## Simulation 2-1
<img width="1572" height="757" alt="Screenshot 2026-10-21 235816" src="https://github.com/user-attachments/assets/e4385340-d123-480c-a39f-9a776285812e" />
<img width="1500" height="757" alt="Screenshot 2026-10-21 235829" src="https://github.com/user-attachments/assets/b4d3b535-fcd0-42da-b6d1-4f9284695776" />
<img width="1532" height="760" alt="Screenshot 2026-10-21 235840" src="https://github.com/user-attachments/assets/09da143b-c302-4b0e-940c-d41f7efbc419" />

## Simulation 2-2
<img width="1572" height="753" alt="Screenshot 2026-10-22 000011" src="https://github.com/user-attachments/assets/10955b6c-e592-41b0-8f55-e94239fcac9d" />
<img width="1488" height="752" alt="Screenshot 2026-10-22 000021" src="https://github.com/user-attachments/assets/3dc18db2-22c4-4ba2-90f7-bced4bc2c444" />
<img width="1532" height="750" alt="Screenshot 2026-10-22 000030" src="https://github.com/user-attachments/assets/982c3094-1850-43b3-b301-0578d8cf7542" />

## Simulation 2-3
<img width="1562" height="752" alt="Screenshot 2026-10-22 000203" src="https://github.com/user-attachments/assets/c1884b40-0892-4249-b793-3d9691adfae7" />
<img width="1512" height="723" alt="Screenshot 2026-10-22 000221" src="https://github.com/user-attachments/assets/2e2b552e-da37-4543-9de3-c92f5c596f4b" />
<img width="1547" height="717" alt="Screenshot 2026-10-22 000234" src="https://github.com/user-attachments/assets/aefd4a1c-a21f-4037-b760-4a4a6acffab3" />

### Discussion/Changes
Once again the design help up pretty well. But I still wasn't happy with how much stress the center piece was facing. I decided to extend the support out and make it longer and hollow it out to save on some material cost.

## Design 3
<img width="841" height="717" alt="Screenshot 2026-10-22 000837" src="https://github.com/user-attachments/assets/2422f27a-cf6e-4462-8153-b64587a40dc2" />

## Simulation 3-1
<img width="1513" height="718" alt="Screenshot 2026-10-22 001412" src="https://github.com/user-attachments/assets/d5f04a3f-bdcb-4fb0-bcd3-7038d6c6ec0e" />
<img width="1521" height="721" alt="Screenshot 2026-10-22 001429" src="https://github.com/user-attachments/assets/69a0974f-a126-4abd-be2f-0ce267810862" />
<img width="1552" height="747" alt="Screenshot 2026-10-22 001440" src="https://github.com/user-attachments/assets/7211a785-f9c5-4475-a49c-d55e634ea636" />

## Simulation 3-2
<img width="1562" height="698" alt="Screenshot 2026-10-22 001600" src="https://github.com/user-attachments/assets/98e11504-df89-4864-bdc2-830809b05fb6" />
<img width="1562" height="740" alt="Screenshot 2026-10-22 001607" src="https://github.com/user-attachments/assets/f44c9818-47ec-4078-a3e0-c870f7650a2b" />
<img width="1547" height="722" alt="Screenshot 2026-10-22 001639" src="https://github.com/user-attachments/assets/1da6c5dc-d22e-4a28-a504-43cf2888f925" />

## Simulation 3-3
<img width="1551" height="706" alt="Screenshot 2026-10-22 001807" src="https://github.com/user-attachments/assets/8e6b540c-ca5d-46bd-8dd4-1dbb6355ca84" />
<img width="1520" height="737" alt="Screenshot 2026-10-22 001818" src="https://github.com/user-attachments/assets/377ed827-f47c-4d74-bfed-3161db5a2ce7" />
<img width="1561" height="698" alt="Screenshot 2026-10-22 001845" src="https://github.com/user-attachments/assets/43173643-e0a4-43a4-9534-ecc5d02fdb79" />

### Discussion/Change
For this final design I decided to bring down the support even farther and to make the edge rounded for an even stronger support.

## Design 4
<img width="921" height="718" alt="Screenshot 2026-10-22 003605" src="https://github.com/user-attachments/assets/7e8cfe1b-07c4-4cd6-9aea-9eeb999949f2" />

## Design 4-1
<img width="1527" height="692" alt="Screenshot 2026-10-22 003929" src="https://github.com/user-attachments/assets/46d13362-a172-4830-836c-d11b12bd8a43" />
<img width="1546" height="741" alt="Screenshot 2026-10-22 003945" src="https://github.com/user-attachments/assets/adc118b1-7719-499e-bed3-1b79d8cc2a6e" />
<img width="1568" height="712" alt="Screenshot 2026-10-22 003953" src="https://github.com/user-attachments/assets/5493ddf2-a3a9-4c29-a237-3b3bdd24cf85" />

## Design 4-2
<img width="1537" height="661" alt="Screenshot 2026-10-22 004123" src="https://github.com/user-attachments/assets/bb4c515f-2e6d-42b2-bf2e-df682ab6ff80" />
<img width="1528" height="728" alt="Screenshot 2026-10-22 004137" src="https://github.com/user-attachments/assets/50a1a504-68af-4b97-86c5-9dfe10ea0738" />
<img width="1536" height="731" alt="Screenshot 2026-10-22 004144" src="https://github.com/user-attachments/assets/7173d94f-7fd3-491d-8653-c9993014659d" />

## Design 4-3
<img width="1513" height="668" alt="Screenshot 2026-10-22 004241" src="https://github.com/user-attachments/assets/db76d480-be24-4b28-a1aa-8f0e3113dda0" />
<img width="1516" height="717" alt="Screenshot 2026-10-22 004250" src="https://github.com/user-attachments/assets/ca3d161c-4342-4d53-93c7-a0cc00219e9d" />
<img width="1552" height="727" alt="Screenshot 2026-10-22 004312" src="https://github.com/user-attachments/assets/2388f1c7-c655-4bf5-8f0e-2c0638c2585b" />

## Discussion/Changes
I know if I keep changing the design I can continue to optimize the bracket. But this final design was the most useful in all categories.

## Reflection

This assignment taught me how to use simulation results to make informed engineering decisions rather than relying solely on the appearance of a CAD model. I learned that identifying areas of high stress helps determine where additional support may be needed, while areas experiencing less stress may offer opportunities to reduce weight. I also gained experience evaluating how the mesh represents the geometry and why simulation results must be verified before making design improvements. One challenge was balancing the accuracy of the analysis with the time required to complete each simulation. Overall, this project strengthened my understanding of the relationship between material selection, structural performance, and design optimization.

**Time Spent:** [5 Hours]
