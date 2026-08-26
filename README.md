# Bluetooth LE GATT Lab

Original Android BLE lab covering discovery and a basic GATT client.

## Features
- BLE scanner with Android 12+ `BLUETOOTH_SCAN`/`BLUETOOTH_CONNECT` runtime permissions.
- Legacy location/Bluetooth permissions capped to Android 11 where appropriate.
- Deduplicated scan results with RSSI.
- Tap a device to connect using GATT, discover services and enumerate characteristics.
- Explicit stop-scan/disconnect/close lifecycle handling.

Best tested on a physical Android device with BLE hardware and a nearby peripheral. No vendor-specific service UUID is assumed.
