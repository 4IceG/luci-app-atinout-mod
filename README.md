# luci-app-atinout-mod

Web UI AT-commands using atinout for OpenWrt.
My luci-app-atinout-mod is modyfication of https://github.com/koshev-msk/luci-app-atinout.

![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/luci-app-atinout-mod?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/luci-app-atinout-mod?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/luci-app-atinout-mod?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/4IceG/luci-app-atinout-mod/total)

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="32"> Preview (modem Quectel EM160R-GL) / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="32"> Podgląd (modem Quectel EM160R-GL)

![](https://raw.githubusercontent.com/4IceG/Personal_data/master/zrzuty/1.9.0/atc.gif)

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="32"> Troubleshooting / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="32"> Rozwiązywanie problemów
``` bash
#Permission denied when sending any AT command.
#Find the file on the router (/ usr / bin / luci-app-atinout) and check if it is executable.
#Execute the command in console.

chmod 755 /usr/bin/luci-app-atinout

```
