# Raspkiosk con Chrome incognito<br>
sudo cp kios.sh /home/pi/<br>
sudo cp kiosk.service /lib/systemd/system/<br>

### Attivare il servizio<br>
sudo systemctl enable kiosk.service<br>
sudo systemctl start kiosk.service<br>

### Pacchetti necessari<br>
sudo apt-get install -y xdotool unclutter sed xscreensaver<br>

### Rimuovere quello non necessario se si vuole<br>
sudo apt-get clean<br>
sudo apt-get autoremove -y<br>
