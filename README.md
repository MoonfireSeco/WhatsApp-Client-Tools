# WhatsApp-Client-Tools
For LunaBot:
- Install TamperMonkey and paste the userscript in there, for ease of use. (remember to make it to not interfere with CSP)
- Set the Content-Security-Policy response header to ```default-src *; report-uri https://dyn.web.whatsapp.com/cspv; script-src * 'unsafe-eval'; connect-src *; img-src * data: blob:; style-src 'self' 'unsafe-inline' *; font-src *; media-src * blob:; child-src *```
- Add a custom refferer=https://products.wolframalpha.com/api/explorer/ for http://www.wolframalpha.com/*
- Add a custom refferer=https://pandorabots.com/mitsuku/ for https://miapi.pandorabots.com/*
- Allow Mixed Content
- Run your browser with the following parameters: **chromium --user-data-dir="LunaBot" --disable-web-security**
- Also you have to manually set the Origin header as 	https://web.whatsapp.com

For LunaBot Discord:
- pip3 install discord
- pip3 install selenium
- pip3 install platform
- pip3 install asyncio
- For chromedriver: `sudo apt-get install chromium-chromedriver` (Then run `dpkg -L chromium-chromedriver` to see where it's located, and correctly specify every path in the LunaBotDiscord.py script)

(Yes, Python3 required)

For ChatterBot Server:
- pip install chatterbot
- pip install cherrypy

For SMTPspoof:
- sudo apt install expect

For SMTPspoofServer:
- pip3 install cherrypy

(Yes, Python3 required)
