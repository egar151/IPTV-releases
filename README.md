# IPTV Appliance — releases

Paquetes firmados (Ed25519) de las actualizaciones OTA del IPTV Appliance para Raspberry Pi.

Cada release contiene:

- `iptv-app-<versión>.tar.gz`: la app (backend y frontend).
- `manifest.json`: versión, nombre del paquete y su sha256.
- `manifest.json.sig`: firma Ed25519 del manifiesto.

Los equipos consultan `releases/latest/download/manifest.json` e instalan solo si la firma es válida. Este repositorio no contiene código fuente.
