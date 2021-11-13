# READ-TST300V2-TEMP.-and-HUMI.-sensors-data-read-using-Modbus-Master-Simulation
Read TST300 V2 temperature and humidity sensor data read using Modbus Master simulation

1.Read Temperature sensor data: 
	At beginning we must identify which port we will use in our laptop. Then, we need to go in my devices application server to figure out this. 
	Download Modbus master simulation below links,
	For reading data from devices, at first, we must setup device settings by simulation.
	Device ID:1, Holding resister, Address-100, Length-2

2.Humedity sensor data read:
	Setup device settings 
	Device ID:3, Holding resister, Address-102, Length-2

3.Read data from meter:
	Setup device settings:
	Device ID:2, Input Resister, Address-0, Length-1

	Modbus RTU setting:
	Port- COM5
	Bitrate-19200
	Parity-Even
	Stop Bit-1

4.Those data send to Node-red: Temperature sensor RTU settings:

<img src= "Modbus-Node cong for Temperature sensor 1.png" width=800>

<img src= "Modbus-Node conf for Temperature sensor 2.png" width=800>
