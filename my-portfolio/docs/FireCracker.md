# FireCracker: Wildifre Prevention Project 

<br>

## Introduction:
FireCracker is an early wildfire detection system, with the goal of providing rural communities with a relaible and cost effective solution to combatting wildfires. 
<br>
<br>

## roject Overview:
Utilizing an ESP32-Wroom32e and many low-power sensors such as CO,CO2, PM2.5, temperature and Humidity, FireCrackers collect important eviromental data. Gathering good enviromental data is crucial for early wildfire detection, avoiding false positives or negatives from non-wildfire smoke sources. FireCrackers conduct data aggregation and don't conduct any form of onboard computting to conserve power.

<br>

## FireCracker Sensor Network Simplified Topology

![Simplified Node Topology](images/FireCrackerImages/data_piepline_trans.png)

 Data is then sent to a collection node for data aggregation, then processed externally by a computation node. By creating a data pipeline that offboards fire detection to a computation node, we're able to minimize power consumption for FireCracker sensors. 
 


 Utilizing a seperate ESP32 as a receiver and a FireCracker sensor as a transceiver, I established communication between the FireCracker and Python. Utilizing this setup I was able to test the FireCracker sensors fire detection capabilities. FireCrackers utilize a two-layer architecture to store enviromental data for long and short term storage. Seperating data storage comes with two advantages, preserving all the data in a csv file for long term analysis and a circular list for fire detection and short-term storage. 

<br>

![FireCracker Sensor](images/FireCrackerImages/board.jpg)
![MPPT-SolarPanel](images/FireCrackerImages/solar_panel.jpeg)

<br>
<br>

## Skills:<br>
1. Data processing <br>
2. Pyserial<br>
3. ESPNOW  <br>
4. Wire.h <br>
5. Embedded Systems <br>

## CAD: <br>
1. OnShape
<br>

## Programming Languages: <br>
1. C++ <br>
2. Python <br>
