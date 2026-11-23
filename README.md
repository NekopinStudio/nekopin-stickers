# Nekopin Stickers

Aplicación Android con 20 stickers de Gers, Poppy, Zia y Lior.

## Compilar sin Android Studio
1. Crea un repositorio privado o público en GitHub, por ejemplo `nekopin-stickers`.
2. Extrae este ZIP y sube **el contenido de la carpeta** a la raíz del repositorio (incluye la carpeta oculta `.github`).
3. Abre la pestaña **Actions** de GitHub y selecciona **Compilar Nekopin Stickers APK**.
4. Pulsa **Run workflow** (o espera a que se ejecute con el push).
5. Cuando termine correctamente, abre la ejecución y descarga el artefacto **Nekopin-Stickers-APK**.
6. Descomprime ese artefacto e instala `app-debug.apk` en tu Android. Abre la app y pulsa **Añadir a WhatsApp**.

La compilación de depuración se firma automáticamente para instalación local. No es una versión firmada para publicar en Google Play. No se ha probado todavía la integración en un dispositivo real.
