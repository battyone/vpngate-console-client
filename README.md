# vpngate-console-client
Simple console client for vpngate (vpngate.net free VPN)

## Dependencies

- wget

- openvpn

- dialog

## Capabilities

- Getting a list of servers

- Sorting the server list

- Adding additional options to the VPN config

- Establishing a connection to the server

## Script variables.

The script is configured by editing the script variables.

### Basic settings.

LISTADDR = "http://www.vpngate.net/api/iphone/" - server list address

LISTFILE = "servers" - a file with a list of servers on the local machine

DATADIR = "./ data" - working directory

DIALOG = "dialog" - a command that calls the dialog utility.

OPENVPN = "openvpn" is the command that calls the openvpn utility.

### Authorization settings.

VPN_LOGIN = "vpn" - login.

VPN_PASS = "vpn" - password

AUTH_FILE = "vpngate.auth" - authorization file

AUTH_DIR = "$ DATADIR" - directory with authorization file.

### Log settings

LOG_FILE = "" - path to the log file

LOG_TTYN = "3" - send log to the terminal whose number is specified in the variable

RMLOG = 0 - delete log upon exiting the program (0 - do not delete, 1 - delete)

LOG_APPEND = 0 - append log (0 - do not append 1 - append)

## Usage

1. Install package (Slackware) or download main script, routing configuration script and VPN options

2. If necessary, change the values ​​of the script variables

3. Change the routing script according to your settings

3. Run the script (vpngate)

4. Update the list of VPN servers (Update VPN List main menu item)

5. If necessary, sort the list of servers and adjust the list of additional VPN options.

6. Select the menu item Connect VPN ...

7. Select the required server and click OK

## Screenshots

![Main Menu] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/01-main-menu.png)

Main menu

![Uploading Server List] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/02-update-vpn-list.png)

Loading the server list

![Preparing Server List] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/03-update-vpn-list.png)

Preparing the server list

![Server list sorting option] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/04-sort-field.png)

Server list sorting option

![Sort order] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/05-sort-order.png)

The sort order

![VPN Options] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/06-vpn-options.png)

VPN options

![Select VPN Server] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/07-select-vpn.png)

Choosing a VPN Server

![VPN Server Information] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/08-vpn-info.png)

VPN Server Information

![Connecting to Server] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/09-vpn-connect-ok.png)

Server connection

![Disconnecting] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/10-vpn-disconnecting.png)

Disconnection

![Window About] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/11-about.png)

About window

![Connection Test] (https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/12-test-final.png)

Connection test
