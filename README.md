## Ex No: 01     Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools   

## Aim:
To design and implement a CMOS inverter circuit using Cadence EDA tools, analyse its electrical characteristics, and understand the fundamental principles of CMOS technology, including the design process, layout, and simulation techniques.

## Tools Required:
•	Personal Computer
•	Cadence Virtuoso Software

## S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window.
2.	Type the following commands as follows and press enter.
	•	csh
        •	source /cadence/install/cshrc
        •	virtuoso

## Procedure for Schematic simulation using Cadence

1.	Now two windows must open
i.      virtuoso/command interpreter window
ii.    ”Whats New…”
3.	Close the 2nd window
4.	Use 1st window i.e virtuoso window (CIW) for further processing.
      i.	Create a New Library
     ii.	Create Schematic Cell view.
    iii.	Create the Symbol for schematic Cell view.
     iv.	Create the test Cell view.
      v.	Analog simulation by spectre


## i)	Procedure for Creating New Library.
1.	File –New – Library
2.	 Name: Give name for ur library Ex: VLSILAB_EXP_1
3.	 Enable Attach to an existing technology library, Click OK
4.	 Attach the library to the technology library gpdk045.Click OK

## ii)	Create Schematic Cell view.
1.	Go to 1st window i.e virtuoso (CIW)
2.	File-New-Cell view
3.	Setup the new file form
4.	Library: Select the one you created.
5.	Cell: Give the experiment name Ex: Inverter ViewSchematic
6.	Type: Schematic press OK
7.	Add the required components from the libraries and make the connections.
8.	Go to instance fixed menu or use shortcut key “I” from keypad to go instances
9.	Click on browse. This opens the library browser
10.	Now select the appropriate library for components like
11.	Gpdk45 ------------------------nmos1v, pmos1v
12.	Create Input and Output pins
13.	Make the connections by using fixed narrow wire key
14.	Click Check and Save button

    
![WhatsApp Image 2024-09-25 at 3 58 05 PM](https://github.com/user-attachments/assets/dec6dc8d-aeac-4a17-b4ad-04ffbf3fdbff)




 
## iii)	Creating the Symbol for schematic Cell view

1.	In the schematic window, execute
2.	Create – Cell view – From Cell view
3.	The cell view from cell view window appears
4.	Check Lib Name, Cell Name, From View name must be schematic Press ok
5.	Now Symbol generation form appears. Click Ok If No changes required
6.	A new window with with default symbol is created.
7.	Edit the symbol if you want to give actual symbol shape else continue.
8.	Execute Create-Cell view-from cell view
9.	Library Name and Cell Name must be same which you have used for schematic. Press OK
10.	Check for the position of pin side.Prss OK
11.	Edit for the shape by Create-Shape-Choose required options to edit.
![vlsi1](https://github.com/user-attachments/assets/4974f93d-5eff-4d80-b9a5-4b0660b85314)






## iv)	Creating the new test cell view

1.	Go to CIW window, Execute File-New-Cell view
2.	Setup the new file form
3.	Library: Select the one you created.
4.	Cell: Cell name must be different from the name used in schematic cell view. Ex: Inverter_test
5.	View: Schematic
6.	Type: Schematic press OK
7.	Follow the step 3(ii) d to make the required connections

 ![WhatsApp Image 2024-09-25 at 3 58 04 PM](https://github.com/user-attachments/assets/9bfd6032-493d-404d-85c9-efb704d4f105)
  




 
## Analog simulation by SPECTRE.
1.	In test cell view window
2.	Launch – ADE L(Analog Design Environment)
3.	Execute Setup—Simulation/directory/Host A new window opens
4.	Set the simulation window to spectre and click ok
5.	Execute Analysis – Choose. A window opens.
6.	Select the type and set the specifications and press OK
7.	Execute Output s—to be plotted – Select on Schematic
8.	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse
9.	Execute Simulation -- Net list and Run

    
![WhatsApp Image 2024-09-25 at 3 58 03 PM (1)](https://github.com/user-attachments/assets/c0cf0aca-7be4-4684-9c8b-7ace313dcd08)



## For Transient Analysis Settings and Output
 
 ![WhatsApp Image 2024-09-25 at 3 58 05 PM (2)](https://github.com/user-attachments/assets/263662ee-6e6c-4cc0-87e0-8fb57b6ab169)



![WhatsApp Image 2024-09-25 at 3 58 02 PM](https://github.com/user-attachments/assets/434e0897-7583-4eda-b3ca-07953b0273e0)



## For DC Analysis Settings and Output


![WhatsApp Image 2024-09-25 at 3 58 05 PM (1)](https://github.com/user-attachments/assets/c1a0c7e4-4540-40b1-8d3d-9d1e8d410d8b)



![WhatsApp Image 2024-09-25 at 3 58 03 PM](https://github.com/user-attachments/assets/f8b395f3-6f6f-4ce6-a87e-784c53f5447e)



 




 

## Results:
1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











