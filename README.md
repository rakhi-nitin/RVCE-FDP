# RVCE-FDP
Implementation of a 4 bit down counter from spec to soc integration 
Step1: write the C model and save
<img width="566" alt="step1" src="https://github.com/user-attachments/assets/55de061e-89cf-433e-9cf8-c2491f6b8152">
Step 2: Run gcc command and print the output
<img width="283" alt="step 1" src="https://github.com/user-attachments/assets/ead1569f-3da4-4e62-bd08-73282e360574">
The output corresonds to O0
step 3:Run the riscv64 commands to convert C model to assembly language
<img width="511" alt="step2" src="https://github.com/user-attachments/assets/f4e0c819-fb6f-43f3-837e-2204507901ca">
<img width="374" alt="step3" src="https://github.com/user-attachments/assets/32576946-f943-4e6d-84fb-2d78d9717125">
step4:check the output of assembly language using spike command. This will be O1
<img width="272" alt="step5" src="https://github.com/user-attachments/assets/db30c9d3-00e5-4e84-bd9d-35d0b8df9f58">
Compare O0=O1. both must be same




