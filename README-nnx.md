
debian build files for 1.2.2 :

cd ..
wget "http://deb.debian.org/debian/pool/main/b/backupninja/backupninja_1.2.2-1.dsc" "http://deb.debian.org/debian/pool/main/b/backupninja/backupninja_1.2.2.orig.tar.gz" "http://deb.debian.org/debian/pool/main/b/backupninja/backupninja_1.2.2-1.debian.tar.xz"
dpkg-source -x backupninja_1.2.2-1.dsc
rm debian
ln -s ../backupninja-1.2.2/debian/

