# Overlay
Overlay for extra Gentoo packages. Probably not what you are looking for and
may break things.


# Install
```
cd /var/db/repos
git clone https://github.com/hodgesds/overlay.git hodgesds

echo -e '[hodgesds-overlay]\nlocation = /var/db/repos/hodgesds/' > /etc/portage/repos.conf/hodgesds.conf
```
