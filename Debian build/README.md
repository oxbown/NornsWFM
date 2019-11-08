# NornsWFM Debian (.deb) package.
 To make the debian package run the following commands:
sudo chmod +x ./NornsWFM/home/we/sidekick/system/'Web File Manager'/run.sh
sudo chmod +x ./NornsWFM/home/we/sidekick/system/'Web File Manager'/stop.sh
sudo chmod +x /home/NornsWFM/DEBIAN/postinst
sudo chmod 775 /home/NornsWFM/DEBIAN/postinst
sudo dpkg-deb --build NornsWFM NornsWFM.deb