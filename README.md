# IPv6-Centos-Azure-Demo
Demo template for two load balanced IPV6 enabled Centos servers in Azure. Uses most of the Microsoft template linked below. Modified to build Centos servers instead of Windows servers. 

References:

Microsoft docs and template:

https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-ipv6-internet-template

Other:

https://alexandrebrisebois.wordpress.com/2015/09/01/create-a-simple-centos-virtual-machine-using-azure-resource-manager/

The Centos images do not have IPv6 DHCP enabled by default. Follow this guide to enable IPv6 on each VM:

https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-ipv6-for-linux
