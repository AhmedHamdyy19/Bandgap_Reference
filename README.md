# Bandgap_Reference

### Circuit Schematic

![alt text](https://user-images.githubusercontent.com/90058055/226418653-ac4bd0ca-8f64-4ec8-91ca-9059a6e10f03.png "Circuit Schematic")
<br>
The design employs Banba's topology with MOSFETs in WI and folded cascode OTA to generate a reference voltage of 0.5V.

### Simulating VDD Variations

![alt text](https://user-images.githubusercontent.com/90058055/226420709-71171fb1-1fb9-4b36-bbc6-3af321fd9dfa.jpg "VDD")
<br>
The design is insensitive to VDD variations in the range 0.8V-1.2V.

### Simulating Temperature Variations

![alt text](https://user-images.githubusercontent.com/90058055/226420878-13d44736-4343-4418-8fda-0a2fd4332a43.jpg "Temp")
<br>
Maximum variation with temperature is 0.5%. The results are good since CTAT and PTAT current can not be perfectly cancelled because the rate of change of VGS with temperature is not perfectly constant.

### Simulating Start-up Time

![alt text](https://user-images.githubusercontent.com/90058055/226422598-45bc0a1b-d04d-488b-9dc8-4576e6da4a13.jpg "Start-up")
<br>
The circuit takes 375ns to start-up in nominal condition. 

### Simulating PSR

![alt text](https://user-images.githubusercontent.com/90058055/226432142-dd0ab042-6863-43b8-bde9-3b5e10036c60.jpg "PSR")
<br>
The circuit has PSR equal to -69 dB at DC.

