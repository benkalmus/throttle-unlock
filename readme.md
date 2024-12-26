copy the .service file to 

cp unlock-throttle.service /etc/systemd/system/unlock-throttle.service

enable this with:
sudo systemctl daemon-reload
sudo systemctl enable unlock-throttle.service

