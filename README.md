# Bluetooth Audio Fix

Run the following command to restart pulseaudio 

```sh
# for specific user
systemctl --user restart pulseaudio.service
```

You can put this inside `~/.profile` to run at login or in `/etc/profile`

## Tested on Debian bookworm kernel 6.1.0-26-amd64
