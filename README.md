# Useful commands

#### for macOS
| Command | Description |
| --- | --- |
| /usr/libexec/ApplicationFirewall/socketfilterfw --setglobalstate on / off | enable / disable firewall |
| /usr/libexec/ApplicationFirewall/socketfilterfw --setstealthmode on / off | enable / disable stealthmode |
| systemsetup -setremotelogin on / off | enable / disable ssh |
| spctl --master-enable / disable| enable / disable gatekeeper |
| dscl . passwd /Users/admin | change user password |
| system_profiler | display any information |
| find / -name "\*filename\*" -print | search and display file |
| whoami | display short username  |
| id -F | display full username |
| osascript -e "long user name of (system info)" | display full username |
| /usr/bin/profiles -I -F /tmp/Trust-Profil.mobileconfig | install profil on macOS |
| /usr/bin/profiles -L | list profiles on macOS |
| /usr/bin/profiles -D | delete profiles on macOS |
| echo y \| sudo /usr/bin/profiles -D | delete profiles on macOS with yes |
| du -hd 1 / | display disk usage |
| tmutil disablelocal | disable local timemachine backups |
| softwareupdate -l | search apple software update |
| softwareupdate -i -a | install available updates |
