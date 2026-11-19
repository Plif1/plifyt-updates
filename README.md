# Plif: actualizaciones

Plif lee `version.json` al abrirse:

- `latest` / `latestName`: la versión más nueva (número interno y nombre que ve la gente).
- `minimum`: la versión más vieja que se puede seguir usando. Si la instalada es menor, Plif obliga a actualizar.
- `apk`: dirección directa del APK (en la carpeta `apk/`).
- `sha256`: huella del APK, para comprobar que llegó entero.
- `notes`: texto opcional que se muestra en el aviso.
