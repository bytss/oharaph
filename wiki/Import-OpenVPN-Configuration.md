OpenVPN servers can generate a configuration file which is bundled with the commands on how to communicate with the server to request a connection.

In Gear VPN, all servers has a configuration data (TCP/UDP). Client (app) takes that connection profile to talk to the server & makes a connection request. If it is accepted by the server you are then connected "to a VPN".

## What is the need for this feature?

As you might know, the app shows some limitated set of servers (that may or might work). But, there are many community hosted servers on the internet which you use for a custom connection through their configuration file.

This gives us flexibility to import any third party server through this connection profile.

## Steps

We will use configuration files from freeopenvpn.org as an example,

- Visit the website. For eg: freeopenvpn.org provides both free & premium servers. This example uses a free server.
- Select any server & click on "Get access" button.

<>

<img src="https://androdevkit.files.wordpress.com/2021/09/free-1.png" width=500px>

<>

- Download any of the configuration (**UDP** or **TCP**) & note the username, password. The configuration file has an .ovpn extension.

- Go to the Gear VPN app > Change Server > Import OpenVPN configuration. From this screen import your .ovpn file & fill the username, password & give a profile name.

<>

<img src="https://androdevkit.files.wordpress.com/2021/09/free-2-1.png" height=350px>

<>

- Now click "Change profile" to switch current profile to this newly created one.
- Just "connect" & you are good to go.

## References

Apart from the example there are many websites that hosts such free configuration file, some of them are listed below.

- https://www.freeopenvpn.org/
- https://nordvpn.com/servers/tools/, (username & password are available in NordVPN's account [dashboard](https://my.nordaccount.com/dashboard/nordvpn/))
- https://www.ovpn.com/en/configurations
