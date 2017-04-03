# BallBounceVGA
Altera DE2-115 FPGA simple VGA interfacing verilog/quartus program template for public use


This barebones verilog program displays a moving image on (any) monitor using the VGA ports. 


# Purpose:

Use this as a template for making verilog games and applications show up on VGA displays.


# Instructions-download:
The source code is in the .v,
the double-clickable quartus project is in the .qpf,
and the pin assignments for the quartus project are in the .qsf.
You don't need any other files. 

# Instructions-software:
Just double-click the .qpf into Quartus, and then Processing->Start_Compilation, and then go to Tools->Programmer, and then in the Programmer pop-up, select JTAG under "Mode", then go to "Hardware Setup" and choose USB-Blaster (google it), and then back up and click "Add File" on the left and select (project)\output_files\BallBounceVGA.osf, and then make sure that "Program/configure" is checked, and lastly click "Start". 

also, make sure the "target device" for your workspace is correct. it should be (Cyclone IV E: EP4CE115F29I7)

# Instructions-hardware:
You need the Altera DE2-115 FPGA for my pin layouts to work.
Simply plug in the VGA cable to the board+monitor, the upload cable to board+computer, and obviously the power to the board. Put the "run/prog" slider switch to RUN.

# video coming soon™
