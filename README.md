# MQTTLocal

uuid-dev is require for mosquitto-1.4.8

uuid-dev is included in util-linux-dev 

on Edison:

```bash
  opkg install util-linux-dev
```

## Mosquitto 

### Password setup

mosquitto_password -c /etc/mosquitto/accesslist.text username
