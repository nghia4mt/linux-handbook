- Edit file `/etc/systemd/logind.conf`
    - Edit in line:
    1. `#HandleLidSwitchExternalPower=suspend` to `HandleLidSwitchDocked=ignore` 
    2. `#HandleLidSwitch=suspend` to `HandleLidSwitch=ignore`
- Apply any changes: `systemctl kill -s HUP systemd-logind`
- See more: [https://wiki.archlinux.org/title/Power_management#Disabling_suspend]
