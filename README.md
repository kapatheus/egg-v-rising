# V Rising

### Custom settings and saves location

You can find the game settings and saves in save-data folder (located at `/save-data`)

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

## Server Ports

| Port            | Default |
| --------------- | ------- |
| Game Port       | 9876    |
| QueryPort       | 9877    |
| RCON (optional) | 25575   |
