# Proyecto Integrado I 

# Trabajo Práctico 1: Solución IoT basada en MQTT sobre entorno WLAN

Este proyecto implementa una solución IoT utilizando el ESP8266, un sensor DHT11 de temperatura y humedad, y una pantalla OLED SSD1306. El dispositivo se conecta a una red WLAN y envía los datos de temperatura y humedad a un servidor MQTT local a través del protocolo MQTT. Además, los datos se visualizan en tiempo real en la pantalla OLED.

## Contenido del repositorio

- Carpeta "src": Contiene el código fuente del programa desarrollado para el ESP8266.
- Carpeta "doc": Contiene la documentación del proyecto, incluyendo el informe del Trabajo Práctico y cualquier otro documento relevante.
- Carpeta "screenshots": Contiene las capturas de pantalla del dispositivo IoT en funcionamiento y otros recursos visuales.

## Requisitos de hardware

- ESP8266
- Sensor DHT11
- Pantalla OLED SSD1306
- Conexiones y componentes adicionales según el esquemático del proyecto

## Instrucciones de instalación

1. Clona este repositorio en tu computadora:
git clone https://github.com/Leytonale/Proyecto-Integrador-I-TP1

2. Conecta el ESP8266, el sensor DHT11 y la pantalla OLED SSD1306 según el esquemático proporcionado.

3. Abre el proyecto en tu entorno de desarrollo preferido (por ejemplo, Arduino IDE).

4. Carga el código fuente en el ESP8266.

## Configuración del servidor MQTT

1. Configura un servidor virtual con un sistema operativo Linux.

2. Instala el broker MQTT Mosquitto en el servidor virtual.

3. Configura las opciones de seguridad, como autenticación y cifrado, según sea necesario.

4. Asegúrate de tener las credenciales y la dirección IP del servidor MQTT para configurar el dispositivo IoT.

## Uso del dispositivo IoT

1. Conecta el dispositivo IoT a una red WLAN doméstica.

2. El dispositivo comenzará a leer la temperatura y humedad del sensor DHT11 y enviará los datos al servidor MQTT.

3. La pantalla OLED mostrará los datos de temperatura y humedad en tiempo real.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar este proyecto, envía tus sugerencias a través de un pull request o abre un issue para discutir tus ideas.

## Licencia

Este proyecto está bajo la licencia [nombre de la licencia]. Consulta el archivo LICENSE para obtener más información.


