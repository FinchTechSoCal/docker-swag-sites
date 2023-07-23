# docker-swag-sites

Copy all configs to proxy-confs.

FILES MUST END IN .subdomain.conf!

Also must restart SWAG or have DOCKER_MODS=linuxserver/mods:swag-auto-reload for configs to take effect.


```bash
git clone https://github.com/FinchTechSoCal/docker-swag-sites.git ~/appdata/swag/nginx/proxy-confs-git
mv ~/appdata/swag/nginx/proxy-confs-git/*.conf ~/appdata/swag/nginx/proxy-confs/
rm -fr ~/appdata/swag/nginx/proxy-confs-git
```