![IMG_20240325_01131368](https://github.com/Arnxb007/Pwnagotchi-on-waveshare-v4/assets/151598485/f1f1d133-2eda-4464-9ad3-833733238367)
# Pwnagotchi
Pwnagotchi is a popular artificial intelligence-driven "hacking" device.  It's designed to passively learn from nearby Wi-Fi networks, using machine learning algorithms to optimize its hacking strategies. Essentially, it's a fun way for cybersecurity enthusiasts to experiment with Wi-Fi security and AI.

Vist the official website for more information: https://pwnagotchi.ai/intro/

# Installation
1. Download this image of pwnagotchi: https://github.com/DrSchottky/pwnagotchi/releases/
2. flash this image on the sd card
3. download the config.toml file ☝️
4. copy the config.toml file to the boot partition 
5.now insert the sd card to the raspberry pi and connect it to your computer using the data port
6. now install the RNDS drivers on your system ☝️ // DEVICE MANAGER > ADD DRIVERS > BROWSE THE COMPUTER > "NAVIGATE TO THE RNDS FOLDER" > NEXT
7. wait for few minutes until a new network device appear
8. now set the IP address and subnet mask //CONTROL PANEL > NETWORK AND INTERNET > NETWORK AND SHARING CENTER > CHNAGE ADAPTER SETTINGS > "NOW FIND USB RNDIS DEVICE" > "DOUBLE CLICK ON THAT " > PROPERTISE > IPV4 > 
   IP ADDRESS "10.0.0.1" , SUBNET MASK "255.255.255.0" > OK
9. open any browser and paste this link: http://10.0.0.2:9000/
10. now give the username and password by default both the password and username is "admin"
11. I f you face difficulty watch this video 👉 https://youtu.be/-VJVQaYVbkQ
