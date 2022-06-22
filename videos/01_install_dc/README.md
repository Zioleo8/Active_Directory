# 01 Installing The Domain Controller

1. Use 'sconfig' to:
    - Change the Hostname
    - CHange the IP Address to Static
    - CHange the DNS Server to our own IP Address

2. Install the Active Directory Windows Features    
'''shell
Install-Windowsfeature AD-Domain-Services -IncludemanagementTools
'''


