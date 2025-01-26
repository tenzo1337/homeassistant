# Home Assistant

Docker Compose for HomeAssistant HASS - MQTT - ZIGBEE2MQTT

## Setup Instructions

### Clone the Repository
Ensure your Linux terminal has Docker and Docker Compose installed, then run:

```sh
git clone https://github.com/tenzo1337/homeassistant.git
```

### Start Containers
This will pre-create some folders:

```sh
docker-compose up -d
```

### Stop Containers
To stop and remove the Docker containers:

```sh
docker-compose down
```

### Configure Zigbee2MQTT
Update `.zigbee2mqtt/configuration.yml` with the MQTT broker's IP address of the server running your MQTT broker.

### Restart Containers
After making changes, restart the containers:

```sh
docker-compose up -d
```

### Access the zigbee2mqtt frontend web ui dashboard
```sh
http://<ip_of_your_zigbee2mqtt_server>:8080
```
