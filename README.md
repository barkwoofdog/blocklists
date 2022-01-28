# blocklists
domains for pihole/dns/ip range blocking

I have a personal vendetta against Samsung and Soundcloud so those will be included and updated as needed.

In order to update your adlists
- Web Console: Group Management > Adlists > copy+paste URL and save CLI: "nano /etc/pihole/adlists.list" (maybe need sudo) 
- add the list URL and save the file. run "pihole -g" to update gravity and you're good to go

You will NEED to add the raw version of the file or else your pihole will spit an error back at you. it does not like formatted pages very well

Here are the links to what to add to your pihole 
- https://raw.githubusercontent.com/barkwoofdog/blocklists/main/samsung-smart-tv 
- https://raw.githubusercontent.com/barkwoofdog/blocklists/main/soundcloud
