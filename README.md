# mirrorlist

```bash
sudo pacman -S reflector
reflector --verbose --connection-timeout 3 --latest 200 --number 40 --sort rate --save <path>
```
