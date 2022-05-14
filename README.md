# sudo-fake
dummy sudo package

# build deb package
chmod 775 sudo-fake/usr/bin/sudo
dpkg-deb --build sudo-fake
