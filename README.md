# blocklists
These are lists of domains I have compiled to be added to pihole (mainly) or whatever DNS blackhole solution that you use.

I have a personal vendetta against Samsung and Soundcloud so those will be included and updated as needed.
Netgear Nighthawk AP's also phone home all the time. I run mine in AP mode since I am using pfsense. Sends about 6K requests a day and is easily the highest on the blocked domain statistics.

## Steps to Update Your Blocklist 
- Web Console: Group Management > Adlists > copy+paste URL and save  
- CLI: ``sudo vim /etc/pihole/adlists.list`` add the list URL and save the file. run ``pihole -g`` to update gravity and you're good to go

You will NEED to add the raw version of the file or else your pihole will spit an error back at you. it does not like formatted pages very well

Here are the links to what to add to your pihole 
- https://raw.githubusercontent.com/barkwoofdog/blocklists/main/samsung-smart-tv 
- https://raw.githubusercontent.com/barkwoofdog/blocklists/main/soundcloud
- https://raw.githubusercontent.com/barkwoofdog/blocklists/main/netgear-nighthawk-ap
