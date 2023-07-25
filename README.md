# Proyecto Integrador I 

# Solución IoT basada en MQTT con visualizacion en Grafana

Este proyecto implementa una solución IoT utilizando el ESP8266, un sensor DHT11 de temperatura y humedad. El dispositivo se conecta a una red WLAN y envía los datos de temperatura y humedad a un servidor MQTT local a través del protocolo MQTT y luego los datos se visualizan en tiempo real en grafana.

## Contenido del repositorio

- Carpeta "src": Contiene el código fuente del programa desarrollado para el ESP8266.
- Carpeta "docs": Contiene la documentación del proyecto, incluyendo el informe del Trabajo Práctico y cualquier otro documento relevante.
- Carpeta "Imagenes": Contiene las capturas de pantalla del dispositivo IoT en funcionamiento y otros recursos visuales.

## Requisitos de hardware

- ESP8266
- Sensor DHT11
- Servidor virtual
- Computadora con 2gb de RAM y 1.3GHz de procesador
- Conexiones y componentes adicionales según el esquemático del proyecto

## Requisitos de Servicios
- Grafana
- MQTT Mosquitto
- Telegraf
- Influxdb

## Uso del dispositivo IoT

1. Conecta el dispositivo IoT a una red WLAN doméstica.

2. El dispositivo comenzará a leer la temperatura y humedad del sensor DHT11 y enviará los datos al servidor MQTT.

3. Se mostraran los datos obtenidos en grafana.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, envía tus sugerencias a través de un pull request o abre un issue para discutir tus ideas.



