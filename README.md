# Blynk Flow Sensor Water Meter

Blynk flow sensor water meter to measure total water consumption. 

<h2> Requirements</h2>
1) Blynk App <br>
2) Water Flow Sensor (I used <a href="images/water-flow-sensor-yf-s201b-product.jpg" target="_blank"> YF-S201B</a>)<br>
3) <a href="images/nodemcu-product.jpg" target="_blank">NodeMCU </a> <br>

<h2> Installation </h2>

Open settings.h and change Bynk Auth code, Wifi settings, server settings and flow calibration. 

<h2> Hardware Connection </h2>

<img src="images/nodemcu-to-water-flow-sensor-connection.png" width="400" height=" " alt="NodeMCU to Water Flow Sensor Connection" title="NodeMCU to Water Flow Sensor Connection">
<br>
<br>
<h3>Flow Sensor to NodeMCU</h3>
<br>
Yellow Wire (Signal Pin) to NodeMCU D2 Pin <br>
Red Wire to NodeMCU 3.3V Pin<br>
Black Wire to NodeMCU Gnd Pin<br>


<h2>Software Setup</h2>
1) Download and install the Blynk Mobile App for iOS or Android. <br><br>
2) Scan the QR code at the bottom of this page to clone the screenshot below, or create a new project yourself and manually arrange and setup the widgets.<br><br>
3) Email yourself the Auth code.<br><br>
4) Download this repo and copy the files in to your sketches directory. Open the sketch in Arduino IDE.<br><br>
5) Go to the settings.h tab. This is where all the customisable settings are. You should be able to change almost everything from there before compiling.<br><br>

<h2> Screenshot</h2>

<img src="images/blynk-flow-sensor-water-meter-screenshot.png" width="350" height=" " alt="Blynk flow sensor water meter screenshot" title="Blynk flow sensor water meter screenshot">


<h2> Scan QR Code on Blynk App </h2>
<img src="images/blynk-flow-sensor-water-meter-qr-code.png" width="350" height=" " alt="Blynk flow sensor water meter QR Code" title="Blynk flow sensor water meter QR Code">

