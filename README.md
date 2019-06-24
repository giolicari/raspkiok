# raspkiosk<br>
raspberry kiosk service<br>
sudo nano /home/pi/kiosk.sh<br>
sudo cp kiosk.service /lib/systemd/system/<br>

### attivare i servizi<br>
sudo systemctl enable kiosk.service<br>
sudo systemctl start kiosk.service<br>

### installazione pacchetti<br>
sudo apt-get install xdotool unclutter sed xscreensaver<br>

### rimuovere software raccomandati per rasp pi 3<br>
sudo apt-get clean<br>
sudo apt-get autoremove -y<br>
