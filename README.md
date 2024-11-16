# AutoTyper-XYZ
This is the downloadable for the console version of the famous NitroType Bot known as AutoTyper XYZ

### Support
- Discord: https://discord.gg/nitrotypebot
- Lifetime Purchase: $20

### Setup
- [Download Python Version 3.11.5](https://www.python.org/downloads/release/python-3115/)
- Download file and extract the zip file
- Set up the config.json
```json
{
    "KEY": "license key",
    "CAPSOLVER": {
        "ENABLE": false,
        "CAPSOLVER_KEY": "capsolver is highly recommended"
    },
    "RACE_FUNCTION":{
        "FAST_MODE": true,
        "WPM_RANGE": [80,90],
        "NITROS": true
    },
    "LOGGING":{
        "ENABLE": false,
        "WEBHOOK": "put webhook link here"
    }
}
```
- Add your NitroType accounts into the file named accounts.txt and be sure to use `username:password` format
- Open command prompt and run `pip install colorama cloudscraper websocket-client paramiko requests capsolver`
- Run main.py or start.bat

Capsolver recommended for the console to work properly, please purchase a key [here](https://dashboard.capsolver.com/passport/register?inviteCode=StGPg6LhBb5j)
Use code `ADSPOWER` for an extra 8% credits!
