# Project


Requirements:
- All VM disks must be encrypted.EBS
- The web server must be backed up daily. The backups must be kept for 7 days.EC2>Enable backup 7 days
- The web server must be installed in an automated manner. EC2>enable install on reboot.User data
- The admin/management server must be reachable with a public IP. public subnet
- The admin/management server should only be reachable from trusted locations (office/admin's home) IAM role AWSA/c IAMUser
- The following IP ranges are used: 10.10.10.0/24 & 10.20.20.0/24 configure VPC and subnets
- All subnets must be protected by a firewall at the subnet level. NACL
- SSH or RDP connections to the web server may only be established from the admin server. Inbound/Outbound using SSH or RDP
