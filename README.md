# Karate Match — proyecto Android

Este proyecto empaqueta el prototipo HTML en una app Android usando Capacitor 6.

## Compilación sin computadora

1. Descomprime este ZIP en el teléfono o tablet.
2. Crea o inicia sesión en GitHub desde el navegador.
3. Crea un repositorio nuevo (por ejemplo `karate-match-android`).
4. Sube todos los archivos y carpetas de este proyecto, incluyendo `.github/workflows/android.yml`.
5. Abre la pestaña **Actions** del repositorio y ejecuta **Build Karate Match APK** con **Run workflow**. También se ejecuta al subir cambios a la rama `main`.
6. Cuando termine correctamente, abre la ejecución y descarga el artefacto **karate-match-apk**.
7. Descomprime el artefacto descargado: dentro estará `app-debug.apk`. Ábrelo para instalarlo.

## Notas

- El APK generado es de depuración e instalable para pruebas; no es un paquete firmado para publicar en Google Play.
- GitHub Actions tiene límites de uso según el tipo de cuenta y sus condiciones vigentes.
- No se necesita acceso a internet dentro del juego después de instalarlo.
- El prototipo original simula un ataque tras cada intercambio adyacente; todavía no implementa la lógica real de combinar tres o más piezas.
