# nagios_openstack

So this is just a breif run through of what can be done.
The ansible wont work on the last piece because the script needs to be moved

Server_ dir: is the server that the nagios is running on

Openstack_dir: is the remote openstack node that you need to have configure to talk back to the master

I threw the order of cfg files and their "Directories" so that the file structure would be seen in a more readable format.

This build is for centos, I may end up building a docker in the end but haven't gotten there yet.

Basic information on install and run through of config is here

https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux_OpenStack_Platform/3/html/Installation_and_Configuration_Guide/chap-Monitoring_OpenStack_using_Nagios.html


Better install information from Nagios it self is here
https://support.nagios.com/kb/article/nagios-core-installing-nagios-core-from-source-96.html#CentOS


Added the rpm for nagios and nagio plugin to the base.

Command for install is rpm -ivh filename.rpm 


Links from the nagios exchange for Openstack monitoring
https://exchange.nagios.org/directory/Plugins/Cloud/openstack_vm_monitoring/details
https://exchange.nagios.org/directory/Plugins/Clustering-and-High-2DAvailability/check_swift/details
https://exchange.nagios.org/directory/Plugins/Clustering-and-High-2DAvailability/check_glance/details


All plugins associated with openstack 
https://exchange.nagios.org/index.php?option=com_mtree&task=search&Itemid=74&searchword=openstack





<br>




Copyright Information
---------------------

Copyright (C) 2018 Jessica Repka

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
