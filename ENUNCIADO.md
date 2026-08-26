# Enunciado didáctico reconstruido — Bluetooth LE y GATT

Laboratorio Android para practicar descubrimiento BLE y conexión como cliente GATT.

La aplicación debe:

1. solicitar los permisos Bluetooth adecuados a la versión Android (`BLUETOOTH_SCAN`/`BLUETOOTH_CONNECT` en Android 12+ y permisos heredados donde corresponda);
2. escanear periféricos BLE cercanos;
3. evitar duplicados en la lista y mostrar, al menos, dirección/nombre disponible y RSSI;
4. permitir seleccionar un dispositivo y establecer una conexión GATT;
5. descubrir sus servicios;
6. enumerar las características disponibles;
7. detener correctamente el escaneo y cerrar/desconectar el GATT cuando ya no se utilice.

La práctica no presupone UUIDs propietarios concretos. Para probarla de forma completa se recomienda un dispositivo Android físico y un periférico BLE cercano.

No existe una base de datos asociada.
