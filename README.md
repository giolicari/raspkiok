# raspkiosk
raspberry kiosk service
sudo nano /home/pi/kiosk.sh
sudo nano /lib/systemd/system/kiosk.service

attivare i servizi
sudo systemctl enable kiosk.service
sudo systemctl start kiosk.service

installazione
sudo apt-get install xdotool unclutter sed

rimuovere software raccomandati per rasp pi3
sudo apt-get clean
sudo apt-get autoremove -y
