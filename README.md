# disableGUI
Guide to disable Ubuntu 22.04 GUI

- The following command will disagle GUI on boot:

`sudo systemctl set-default multi-user`

- Reboot or exit current session to exit GUI:

`reboot`
or
`sudo init 3`

- To start GUI manually from command line:

`sudo systemctl start gdm3`

- To re-enable GUI at startup

`sudo systemctl set-default graphical`

