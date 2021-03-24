# luci-app-atinout-mod

Web UI AT-commands using atinout for OpenWrt.
My luci-app-atinout-mod is modyfication of https://github.com/koshev-msk/luci-app-atinout.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/luci-app-atinout-mod?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/luci-app-atinout-mod?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/luci-app-atinout-mod?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/4IceG/luci-app-atinout-mod/total)

### Preview and quick configuration (modem Quectel EM12-G) / Podgląd oraz szybka konfiguracja (modem Quectel EM12-G)

![](https://raw.githubusercontent.com/4IceG/Personal_data/master/atcommands.gif)

### Troubleshooting / Rozwiązywanie problemów
``` bash
#Permission denied when sending any AT command.
#Find the file on the router (/ usr / bin / luci-app-atinout) and check if it is executable.
#Execute the command in console.

chmod 755 /usr/bin/luci-app-atinout

```

