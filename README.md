# Overlay
Overlay for extra Gentoo packages. Probably not what you are looking for and
may break things.


# Install
```
cd /var/db/repos
git clone https://github.com/hodgesds/overlay.git hodgesd

echo -e '[hodges-overlay]\nlocation = /var/db/repos/hodgesd/' > /etc/portage/repos.conf/hodgesd.conf
```
