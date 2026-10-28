# A8 – Gear Box Design

# Objective
- Designed a gearbox for assembly and disassembly.
- Analyzed and sized input and output shafts for strength.
- Designed journal bearings to support rotating shafts.
- Created a gearbox housing with proper clearances and fastening features.
- Used parametric CAD modeling to develop the final design.
- Documented engineering calculations, sketches, and lessons learned.

## Shaft Design
### Design Knowns

- Gear Ratio: 24:9
- Output Gear Torque: 1.25 in-lbf
- Output Gear Speed: 1100 rpm (relative)
- Input (Pinion/Power-Transmission) Shaft Diameter: 0.125 in
- Shaft Length: 1.00 in
- Output (Gear/Short Shaft) Shaft Diameter: 0.250 in
- Power Shaft Strength: 4000 psi
- Output Shaft Strength: 8500 psi
### Design Unknowns  
- Input Speed and Torque
- Input Shafts Torque
- Output Shafts Torque

## Freebody Diagram (FBD)
<img width="815" height="740" alt="IMG_0417" src="https://github.com/user-attachments/assets/c5b94136-b4d3-449a-80eb-abed58a9d2b1" />

## Equations
<img width="1683" height="635" alt="IMG_0418" src="https://github.com/user-attachments/assets/e34eb8ea-94cb-4c8c-9382-4784e88ce91f" />
<img width="1532" height="779" alt="IMG_0419" src="https://github.com/user-attachments/assets/c1a90787-7747-4092-9fa6-c1db7ad0035d" />

## Numerically Solved
<img width="1413" height="766" alt="IMG_0420" src="https://github.com/user-attachments/assets/ffae20bd-74b5-4f10-b3f8-971aec249429" />
<img width="1489" height="1019" alt="IMG_0421" src="https://github.com/user-attachments/assets/24f14d00-1598-4fd8-af0e-c01d380b0123" />

## Bearing Design
### Design Knowns
- Power: 0.022 hp
- Input Torque: 0.468 in-lbf
- Output Torque: 1.25 in-lbf
- Input Speed: 2933 RPM
- Output Speed: 1100 RPM
- Input Gear Shaft Diameter: 0.125 in
- Output Gear Shaft Diameter: 0.250 in
- Shaft Length: 1.00 in
- RC5 Clearance: 0.001 in

### Design Unknowns
- Bearing Thickness: in
- Bearing Material: ???

## Freebody Diagram (FBD)
<img width="1344" height="686" alt="IMG_0422" src="https://github.com/user-attachments/assets/507887dc-6e8f-4b20-9214-66531970a341" />

## Equations
<img width="517" height="1095" alt="IMG_0423" src="https://github.com/user-attachments/assets/1ebc5fa8-9e00-40cf-b282-08c0df4a5812" />
<img width="1084" height="858" alt="IMG_0424" src="https://github.com/user-attachments/assets/b6e07103-b429-4e8e-93db-3c256fd5beb2" />

## Numerically Solved
<img width="1089" height="1100" alt="IMG_0425" src="https://github.com/user-attachments/assets/506364d8-1d5c-4bf8-809d-228957ee0400" />
<img width="979" height="534" alt="IMG_0427" src="https://github.com/user-attachments/assets/76172bb7-1f15-44bd-9e9a-4257bc7b858a" />

## McMaster Parts
[Gearbox Bolt](https://www.mcmaster.com/91251A102/)
[Bearing Sleeve 1](https://www.mcmaster.com/6391K111/)
[Bearing Sleeve 2](https://www.mcmaster.com/6391K136/)
[Big Gear](https://www.mcmaster.com/6832K45/)
[Shaft](https://www.mcmaster.com/1327K113/)
[Little Gear](https://www.mcmaster.com/7880K17/)
[Small Shaft](https://www.mcmaster.com/1327K93/)

## Gearbox Drawing
<img width="1291" height="1140" alt="IMG_0428" src="https://github.com/user-attachments/assets/89bf6f97-2ab8-4ce8-afa0-53acd84e7064" />

## Material Choice
I decided to use an Alloy Steel because it was the most generic material I could think of. And its what most industries use as their material.
<img width="895" height="293" alt="Screenshot 2026-10-28 180921" src="https://github.com/user-attachments/assets/4211736d-fdcd-4e9a-ab95-2844f11b40ac" />

## Model Variables
<img width="598" height="305" alt="Screenshot 2026-10-28 180742" src="https://github.com/user-attachments/assets/6966fa91-f5da-4831-b318-9ff440c9503f" />

## Model
I decided to make the box a 3in long by 2in tall box and decided to extrude the length of the box by 3in to max the longest shaft in my model
<img width="922" height="562" alt="Screenshot 2026-10-28 192004" src="https://github.com/user-attachments/assets/4fbf5901-2056-4d83-bcae-4ece4125cc7e" />
<img width="732" height="682" alt="Screenshot 2026-10-28 192352" src="https://github.com/user-attachments/assets/946961a9-7ab7-4546-9860-259fc1a017a3" />

## Lesson Learned
I learned about Mcmaster and that it has just about every single cadfile on hand and you can download them for free to include in any model you have. I was used to the assembly portion because that was covered in a prevoius class I took. It took me about 5 hours to solve everything and model it together.

## Files
[CAD File](
