###  In the same folder, download mosquitto.conf and run the command below to get an mqtt broker running on your machine

```
sudo docker run -it --rm -p 8883:8883 -p 9001:9001 -v "$(pwd)/mosquitto.conf:/mosquitto/config/mosquitto.conf" eclipse-mosquitto
```
