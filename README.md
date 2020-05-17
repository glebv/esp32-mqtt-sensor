# ESP-MQTT-WIFI sample application

* Open the project configuration menu (`idf.py menuconfig`)
* Configure MQTT App Configuration
    * wifi settings: ssid, password, Maximum retry
    * mqtt settings: mqtt broker url, mqtt username, mqtt password
* Flash by `idf.py -p /dev/tty.SLAB_USBtoUART -b 921600 --ccache flash monitor`

