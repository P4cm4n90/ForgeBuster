This script was written as an exploit for Forge HTB Machine
It enables us to access admin.forge.htb by exploiting SSRF vulnerability of forge.htb.
Shortly speaking it abuses upload image from link capability (there are no upload restrictions but direct access of localhost urls is blacklisted). 
We can bypass upload restrictions by creating out http server that redirects to admin.forge.htb which can be access only from localhost
