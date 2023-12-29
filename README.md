Shelly Pro 3EM into Victron DBUS version for single phase setup
based on: https://github.com/funkmaster86/dbus-shelly-pro-3em-smartmeter

I'm not a programer, use it on your own risk...

Installation:
```
wget https://github.com/Picard0147/dbus-shelly-pro-3em-smartmeter-1phase/archive/refs/heads/main.zip
unzip main.zip "dbus-shelly-pro-3em-smartmeter-1phase-main/*" -d /data
mv /data/dbus-shelly-pro-3em-smartmeter-1phase-main /data/dbus-shelly-pro-3em-smartmeter-1phase
chmod a+x /data/dbus-shelly-pro-3em-smartmeter-1phase/*.sh
/data/dbus-shelly-pro-3em-smartmeter-1phase/install.sh
rm main.zip
```
