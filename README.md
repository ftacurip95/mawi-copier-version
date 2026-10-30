# Mawï Copier — versiones

Aquí se publican los instaladores de **Mawï Copier para clientes**, uno por versión.

```
latest.json            ← dice cuál es la última versión (firmado por Mawï); la app lo consulta para avisar de actualizaciones
clientes/
  v2.0.0/              ← instalador (.exe), APK de Android, manual (.pdf), LEEME y huellas SHA-256 de esa versión
  v1.2.4/
```

- Para instalar: entra a la carpeta de la versión y descarga `MawiCopier-Setup-X.Y.Z.exe`.
- Cada versión queda completa en su propia carpeta; no se borran las anteriores.
- `latest.json` lo genera y firma `tools/publish_update/publish_update.py` (del proyecto privado). No se edita a mano.
