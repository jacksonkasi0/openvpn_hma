    __  ___     __     __  ___      ___              __
   / / / (_)___/ /__  /  |/  /_  __/   |  __________/ /
  / /_/ / / __  / _ \/ /|_/ / / / / /| | / ___/ ___/ / 
 / __  / / /_/ /  __/ /  / / /_/ / ___ |(__  |__  )_/  
/_/ /_/_/\__,_/\___/_/  /_/\__, /_/  |_/____/____(_)   
                          /____/                 
						  
           - https://www.hidemyass.com -
         - https://support.hidemyass.com -
				
--------------------------------------
   HMA! Pro VPN Linux Scripts Pack 
--------------------------------------

Contents:

* hma-openvpn.sh
* hma-vpn-old.sh
* hma-vpn.sh

Description:

* hma-openvpn.sh
= v0.x Dialog-based OpenVPN connection script; asks for server & protocol choice (TCP/UDP)
- Features: daemon-mode, server-pingtest, auto-connect to fastest server, show status, update function 
- Requires packages: curl wget openvpn dialog sudo fping

* hma-vpn.sh
= v2.x (Beta) of our original script with various improvements, such as protocol choice (UDP/TCP), daemon mode, 
  auto-login, port choice, update function, show status, server-pingtest, auto-connect to fastest server, etc. 
- Required packages: curl wget openvpn sudo fping
    
* hma-vpn-old.sh
= Official, original Linux script as available in the VPN control panel in the past (v1.3)
  Included for legacy reasons in case of trouble with the new scripts
- Requires packages: curl wget openvpn sudo

-----------------------

Which script to choose?

* For Linux beginners we recommend using the "hma-openvpn.sh" script by simply running "./hma-openvpn.sh" 
  or "bash hma-openvpn.sh". This script asks you for only the most basic required 
  information (server-choice, protocol, username, password) and establishes a connection.

* For advanced Linux users we recommend the "hma-vpn.sh" script as it offers 
  a variety of additional features for various purposes.

* If for some reason you prefer the "old" script or the other two scripts won't work for you, 
  you can use the legacy version by running "./hma-vpn-old.sh" respectively "bash hma-vpn-old.sh"

----------------------

Related links:

- HMA! Website: https://www.hidemyass.com

- VPN Control Panel: https://vpn.hidemyass.com
  (Manage your account, subscription, get server IPs and hostnames, etc.)

- HMA! Support and Knowledge Base: https://support.hidemyass.com

- Knowledge Base "Linux" category: https://hmastuff.com/linux-kb
  (For more tutorials and instructions about Linux VPN connection methods)
