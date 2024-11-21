# Azure-IoT-Central ESP32-device

#### This example demonstrates an ESP32 S3 development board running the Azure SDK and C++ code to connect and send telemetry data (temperature and humidity) to Azure IoT Central.

#### The file Azure_IoT_PnP_Template.cpp was modified to include the code to use DHT22 sensor, to capture temperature and humidity telemetry. 
#### All other default telemetry information originaly included in the Azure SDK was removed from the file Azure_IoT_PnP_Template.cpp.
#### Omly the DHT22 sensor Temperature and Humidity telemetry is sent to the Azure IoT central after this modification

The DPS_ID_SCOPE, IOT_CONFIG_DEVICE_ID, and IOT_CONFIG_DEVICE_KEY information from the IoT Central application, need to be populated in the iot_config.h file.

![WIN_20241120_07_50_46_Pro](https://github.com/user-attachments/assets/6629a7c9-419c-4b3c-9f7f-f0cf4df42c98)


![IoT Project](https://github.com/user-attachments/assets/c9d86271-c83f-4879-9310-c8c641d8e564)
