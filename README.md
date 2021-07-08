# Li-FI-indoor-navigation-system

# Aim

The aim of the project was to create a Li-Fi-based indoor navigation system.

# Description

The system created so far utilizes LEDs connected to a NodeMCU to send data to a server. It utilizes Djikstra's algorithm to find the shortest path between two points, and the data collected is stored using MongoDB.

# Working

Data is encoded in light by varying the rate with which LEDs switch between ON and OFF states. This light falls upon a detector, such as an LDR, which in turn transmits these variations to the development board - in this case, the ESP8266. The information transmitted consists of location data, which is in turn stored in a database using MongoDB. An architecture is created through the Djikstar Python library, which uses Djikstra's algorithm to find the shortest path.

# Motivation

Indoor navigation systems assume importance due to the fact that systems like the GPS cannot provide this functionality. 

Li-Fi becomes a good candidate to base such a system upon because it offers higher speed of communication as compared to Wi-Fi. It comprises of LEDs transmitting data using visible light. The usage of LEDs reduces energy consumption by 50%.
The transmissions themselves are invisible to the human eye and hence cause no inconvenience. 
