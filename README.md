# MTX-BC48-DB-Development-Board
The MTX-BC48-DB is an easy-to-use platform to develop and demonstrate various features of the iCE40 UltraPlus for Bluetooth Low Energy communication and Image processing. 

Folder contain the project zip file "CameraCube_Image_Transfer.zip".
To be able to use, unzip and build using Lattice Semiconductor "Radiant" design software.
Project performs:
1. After power up, the FPGA is configurating by project “CamerCube_Image_Transfer_impl_1.bin” file
2. After FPGA configuration done, the "Config Done" LED is flashing steadily 
3. The CameraCube image sensor OV7690 is configuring.
4. After configuration finished, the "Heart Beat" LED is flashing with the pulsing.
5. The image data from the Image Sensor “Camera Cube” appears on the pins of “Dbg/Prg Connector”:
    o_image_data_gate 	pin 4
    o_image_data_enb	  pin 5
    o_image_data(0)    	pin 9
    o_image_data(1)    	pin 1
    o_image_data(2)    	pin 8
    o_image_data(3)   	pin 2
    o_image_data(4)   	pin 6
    o_image_data(5)    	pin 3
    o_image_data(6)    	pin 7
    o_image_data(7)    	pin 10

