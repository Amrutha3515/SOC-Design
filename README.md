# SOC-Design
<details>
<summary> DAY-1: Introduction to Openlane and Synthesizing the Picorv32A </summary>
  
1.To open OPENLANE, docker command can be used which responds with bash-4.2 <br><br>
2.Enter into interactive mode of operation a command ``` ./flow.tcl -interactive ``` <br><br>
3.Further, the required version of openlane to be defined which is openlane 0.9 using command ```package require openlane 0.9 ```<br><br>
4.Select the design using command ```prep -design picorv32a```, design folder.<br><br>
5.Then all LEF files will be merged.<br><br>

  ![Screenshot 2024-10-04 071123](https://github.com/user-attachments/assets/a0e0e0eb-01aa-4ecc-b7ce-870f80ac4019)

Once the preparation is complete, a new directory with the current date will be generated within the “runs” folder. Inside this directory, all the necessary subdirectories for storing results, reports, and other relevant data will be created.

![Screenshot 2024-10-04 071525](https://github.com/user-attachments/assets/e7d1fec6-7e9f-4dd3-b3dc-1f509b3af2e1)

In bash prompt, give the command <run_synthesis>, then synthesis will be done on the design if errors are not observed.

![Screenshot 2024-10-04 072226](https://github.com/user-attachments/assets/f7ce0737-6485-47b1-9316-331b4d60446b)

The number of D-flip flops observed in the synthesis report is shown below which conveys that there is 10.48% of flops available in the total number of cells.

![Screenshot 2024-10-04 072401](https://github.com/user-attachments/assets/d4222554-9bd0-4d3f-8e18-b3791ddfbf0b)

![Screenshot 2024-10-04 072427](https://github.com/user-attachments/assets/744f6882-0e67-4976-8f85-b28082e74a08)

![Screenshot 2024-10-04 073512](https://github.com/user-attachments/assets/0017f6f1-18d2-452c-95cc-114ebf661175)
Synthesis process also provides reports over timing, no. of cells etc, on among which is shown below:
![Screenshot 2024-10-04 073044](https://github.com/user-attachments/assets/0b422a0b-ef2f-4eed-95a5-4b51a84793ef)

![Screenshot 2024-10-04 073431](https://github.com/user-attachments/assets/fe7fef75-47b8-4dd5-ab13-e70566f6d455)

</details>

<details>
  <summary>DAY-2: Floorplan and Placement</summary>

  
</details>
