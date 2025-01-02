# AutoTyper-XYZ
This is the downloadable for the console version of the famous NitroType Bot known as AutoTyper XYZ

### Support
- Discord: https://discord.gg/wbgNQUUj
- Lifetime Purchase: $20

### Setup
- [Download Python Version 3.11.5](https://www.python.org/downloads/release/python-3115/)
- Download file and extract the zip file
- Set up the config.json
```json
{
    "KEY": "", Your License Key
    "CAPSOLVER": {
        "ENABLE": false, Enables Capsolver (True or False)
        "CAPSOLVER_KEY": "" Capsolver Key
    },
    "RACE_FUNCTION":{
        "FAST_MODE": true, Races Faster (True or False)
        "WPM_RANGE": [80,90], Bot WPM Min speed and Max Speed
        "ACCURACY_RANGE": [85,100], Bot Min Accuracy and Max Accuracy
        "NITROS": true, Use Nitros (True or False)
        "STICKERS": false, Use Stickers (True or False)
    },
    "LOGGING":{
        "ENABLE": false, Discord Webhook Logging (True or False)
        "WEBHOOK": "" Insert Discord Webhook URL Here 
    }
}
```
- Add your NitroType accounts into the file named accounts.txt and be sure to use `username:password` format
- Open command prompt and run `pip install colorama fake-useragent cloudscraper websocket-client paramiko requests capsolver pycryptodome random-word`
- Run main.py or start.bat

Capsolver recommended for the console to work properly, please purchase a key [here](https://dashboard.capsolver.com/passport/register?inviteCode=StGPg6LhBb5j)
Use code `ADSPOWER` for an extra 8% credits!
