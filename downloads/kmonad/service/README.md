
Installing as a Systemd service
===============================

To enable auto-run on Linux-based systems:

0. *Change file paths to suit you own system*

1. `cp kmonad.service ~/.local/share/systemd/user/kmonad.service`

2a. `systemctl --user enable kmonad.path` (if first install)

2b. `systemctl --user  daemon-reload` (if updating exising file)

To manually turn on and off:

`systemctl --user start kmonad.service`
`systemctl --user stop kmonad.service`
