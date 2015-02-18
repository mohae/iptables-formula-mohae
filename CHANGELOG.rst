firewall formula
================

0.1 (01-05-2014)

- Initial version with support just for iptables

0.1.1 (02-16-2015)

- Separate out iptables processing  
- Add `init.sls` state  
- Add specification of ports and protocol w/o source ips to `iptables.sls`
- Remove strict option from `iptables.sls`, firewalls should be strict by default.
- Update README
- Update `pillar.example`
- Add state for purging `ufw` on Ubuntu and removing associated files from `/etc/ufw`
 