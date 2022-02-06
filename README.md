# My Build of suckless.org slock tool

Source: https://tools.suckless.org/slock/

## Applied patches
- blur pixelated screen
- dpms
- mediakeys
- pam auth

## Run it with xautolock
for example inside of xinit

```
xautolock -time 1 -locker slock -killtime 10 -killer "systemctl suspend" &
```
