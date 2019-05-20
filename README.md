# raspkiosk
raspberry kiosk service
sudo nano /home/pi/kiosk.sh
sudo nano /lib/systemd/system/kiosk.service

attivare i servizi
sudo systemctl enable kiosk.service
sudo systemctl start kiosk.service

installazione pacchetti
sudo apt-get install xdotool unclutter sed xscreensaver

rimuovere software raccomandati per rasp pi 3
sudo apt-get clean
sudo apt-get autoremove -y
