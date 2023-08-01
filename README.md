# docker-swag-sites

Copy all configs to proxy-confs.

FILES MUST END IN .subdomain.conf!

Also must restart SWAG or have DOCKER_MODS=linuxserver/mods:swag-auto-reload for configs to take effect.


```bash
git clone https://github.com/FinchTechSoCal/docker-swag-sites.git ~/appdata/swag-git
mv ~/appdata/swag-git/*.conf ~/appdata/swag/nginx/proxy-confs/
rm -fr ~/appdata/swag-git/
```