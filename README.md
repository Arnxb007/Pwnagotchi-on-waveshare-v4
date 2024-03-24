# Pwnagotchi
Pwnagotchi is a popular artificial intelligence-driven "hacking" device.  It's designed to passively learn from nearby Wi-Fi networks, using machine learning algorithms to optimize its hacking strategies. Essentially, it's a fun way for cybersecurity enthusiasts to experiment with Wi-Fi security and AI.

Vist the official website for more information: https://pwnagotchi.ai/intro/

# Installation
1. Download this image of pwnagotchi: https://github.com/DrSchottky/pwnagotchi/releases/
2. flash this image on the sd card
3. create a new file in boot partition "config.toml" and paste the code below👇
# config.toml
main.name = "pwnagotchi"
main.lang = "en"
main.whitelist = [
"EXAMPLE_NETWORK"
]
main.plugins.grid.enabled = true
main.plugins.grid.report = true
main.plugins.grid.exclude = [
  "YourHomeNetworkHere"
]

ui.display.enabled = true
ui.display.type = "waveshare_3"
ui.display.color = "black"

ui.web.username = "admin"
ui.web.password = "admin"
ui.web.enabled = true
ui.web.address = "0.0.0.0"
ui.web.origin = ""
ui.web.port = 9000
