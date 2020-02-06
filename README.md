# Pub-Sub Paho-Mqtt
Python Scripts for MQTT Publish and Subcribe
List of files:
1.) pub.py 
2.) data.json
3.) pub_conf.json
4.) sub.py
5.) sub_conf.json

data.json - Put required data in json format in data.json and pub.py sends that file as a msg-payload max size limit upto(255 mb)
pub_conf - publisher configuration such as broker address, port and topic
sub_conf - subscriber configuration such as broker address, port and topic

Usage
- python pub.py --conf \path\of\pub_conf.json --data \path\of\data.json
- python sub.py --conf sub_conf.json