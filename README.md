# check_sap_sm58.py
Nagios plugin for checking SAP Transactional RFC - sm58 


Usage:./check_sap_sm58.py \<SID\> 

Example:
root@:~/github# ./check_sap_sm58.py SBX 

SAP*;SBX-001-COMASTER;

                                                                      
### Prerequisite:
https://github.com/piersharding/python-sapnwrfc

### Wiki:
Installation of sapnwrfc for python on Linux and Unix
https://wiki.scn.sap.com/wiki/display/EmTech/Installation+of+sapnwrfc+for+python+on+Linux+and+Unix






To prepare a script, you'll need a 'yml' file similar to the 'sap.yml' file included with the sapnwrfc download. The file looks 

like this:
#### Example of SID.yml file

ashost: gecko.local.net

sysnr: "01"

client: "001"

user: developer

passwd: developer

lang: EN

trace: 3

loglevel: warn
