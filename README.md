# Pulse · versiones

Este repositorio sólo publica las versiones de **Pulse** (RetrOx Devs): el paquete de cada versión, el instalador y su manifiesto firmado (`release.json` + `release.json.sig`). No contiene código fuente.

Cada instalación de Pulse acepta una versión sólo si la firma Ed25519 del manifiesto es válida con la clave pública que trae instalada, y nunca una versión más vieja que la que tiene. Un archivo modificado o ajeno se rechaza.
