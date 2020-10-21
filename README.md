# Chatroom
---
## Config
```json
{
    "apiKey": "",
    "authDomain": "",
    "databaseURL": "",
    "projectId": "",
    "storageBucket": "",
    "messagingSenderId": "",
    "appId": ""
}
```
To use this app, please rename the "config.sample.json" file under the src/ folder to "config.json".
All the fields should be taken from firebase by adding your web app to the firebase project. This can be done by:
1. Clicking the gear next to "Project Overview"
2. Clicking "Project settings"
3. Under your apps click the web icon to add a web app
4. Navigate to your config info and copy that to paste it in the "config.json" file