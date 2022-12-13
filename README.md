# Trabajo practico final para la materia Desarrollo de aplicaciones para IoT
## Martin Brocca

### Estructura de carpetas:

    +-- _Azure_IoT_Central_ESP32
        +-- AzureIoT.cpp
        +-- AzureIoT.h
        +-- Azure_IoT_Central_ESP32.ino
        +-- Azure_IoT_PnP_Template.cpp
        +-- Azure_IoT_PnP_Template.h
        +-- iot_configs-Template.h
        +-- readme.md
    +-- _Azure_IoT_Hub_ESP32
        +--AzIoTSasToken.cpp
        +--AzIoTSasToken.h
        +--Azure_IoT_Hub_ESP32.ino
        +--SerialLogger.cpp
        +--SerialLogger.h
        +--iot_configs-Template.h
        +--readme.md
    +-- Azure_IoT_Hub_ESP32_TLS
        +--AzIoTSasToken.cpp
        +--AzIoTSasToken.h
        +--Azure_IoT_Hub_ESP32.ino
        +--SerialLogger.cpp
        +--SerialLogger.h
        +--iot_configs-Template.h
        +--readme.md

Todos los trabajos estan basados sobre los ejemplos propuestos en el [repositorio oficial de Microsoft](https://github.com/Azure/azure-sdk-for-c-arduino) 

Los proyectos fueron realizados mediante uso de las librerias del *azure-sdk-for-c-arduino* que incorpora manejadores de conexion con los sistemas de Azure IoT.
Para el correcto funcionamiento, se deberan configurar los archivos *iot_config.h* basados en el template incorporados, omitidos aqui debido a los secretos que incorpora.


