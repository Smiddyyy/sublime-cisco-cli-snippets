# sublime-cisco-cli-snippets

Sublime Text Cisco-Cli Snippets. Includes various routing/firewall configurations. For Cisco Router ISO '1562.T'.

## Installing
Clone the repository into Sublime Text "Packages/Cisco" directory (Preferences -> Browse packages):
	```
    	git clone git@github.com:Smiddyyy/sublime-cisco-cli-snippets.git
	```
## Usage
To use the snippets, type the snippet name then hit tab. Some snippets have multiple options. You can Tab through the Configurations. Available snippets are:

* `default` - Creates a default configuration
* `int` - Creates a Interface configuration (optional: with ospf authentication)
* `lo` - Creates a Loopback-Interface configuration (optional: with ospf authentication)
* `tun` - Creates a Tunnel-Interface (optional: dmvpn-hub / dmvpn-spoke)
* `ospf` - creates an Ospf-process 
* `bgp` - creates a BGP-process
* `zbfw` - creates a Zone Base Firewall Configuration
* `/24` - Maps to 255.255.255.0 (optional: inverts it to 0.0.0.255)
* `/32` - Maps to 255.255.255.255 (optional: inverts it to 0.0.0.0)
* `help` - information about DHCP, DNS, HTTP and SYSLOG configuration

## Official Website
official website for further information.
[http://www.tunnelsup.com/tup/2013/03/29/sublime-text-2-cisco-syntax-and-snippets](http://www.tunnelsup.com/tup/2013/03/29/sublime-text-2-cisco-syntax-and-snippets)
