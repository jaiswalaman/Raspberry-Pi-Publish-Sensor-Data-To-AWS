# Raspberry-Pi-Publish-Sensor-Data-To-AWS
CSN-252 ESD-2
This project is based on Raspberry Pi. In this project we are publishing Temperature and
Humidity Sensor Data to AWS - IoT using Raspberry Pi. We are viewing the data sent to
AWS through a MQTT client app. The Temperature and Humidity is also displayed on a
LCD screen connected to Raspberry Pi. We can access the sensor data from anywhere in the
world if we have the certificates and keys that are required for authenticating the connection
to AWS. We have created an AWS Thing(iot device) for our sensor and generated certificates
and policies and used the same for connecting MQTT client to AWS. The security protocols
used are SSL/TLS. We have implemented the code in python and executed it on Raspberry
Pi
