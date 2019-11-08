# Automount External drives into Norns
There are 3 files:

/etc/udev/rules.d/usbstick.rules

/lib/systemd/system/usbstick-handler@.service

/usr/local/bin/automount


automount needs chmod +x to run..

sudo chmod +x /usr/local/bin/automount