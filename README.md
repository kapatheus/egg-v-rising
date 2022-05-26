# V Rising

### Custom settings and saves location

You can find the game settings and saves in save-data folder (located at `/save-data`)


### Server Settings

List of V Rising Server Settings, with a description of what each setting does and the min/max values where applicable.
https://cdn.stunlock.com/blog/2022/05/25083113/Game-Server-Settings.pdf


### Server Updating
You can update the server by reinstalling it. This should not affect the existing save-data folder files, but remember to ALWAYS take a backup before updating/reinstalling. 


### RCON

This does not yet include the automatically generated RCON conf, but you can add it yourself.
To enable RCON, add the following to the server host settings file (located at `/save-data/Settings/ServerHostSettings.json`):
```
"Rcon": {
  "Enabled": true,
  "Password": "somepassword",
  "Port": 25575
}
```

There are reports that using RCON can cause your server CPU to max out, so use at your own risk for now.
I haven't got this to work as expected yet, I recommend waiting for an update here.


## Server Ports

| Port            | Default |
| --------------- | ------- |
| Game Port       | 9876    |
| QueryPort       | 9877    |
| RCON (optional) | 25575   |
