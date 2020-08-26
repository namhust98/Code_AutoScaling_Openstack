# Code_Openstack
Overview
--------
This code for auto scaling in openstack Queen, with Ubuntu 16.04

How to use
----------

First, you need install python3 to your system

Then, you need run your openstack and reconfig your information to "admin-openrc" and "demo-openrc" file

Finally, run this code with command `$sudo bash auto_scale` to auto scaling, or run `$sudo bash auto_scale_up` if you just need the scale up

Function
--------

When you run this code, if the CPU uses more than 80%, openstack will create a new image, if the CPU use less than 20%, openstack will turn off one image
