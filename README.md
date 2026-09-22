<div align="center">

✨ Lyra Lazuli Life ✨

El gestor de biblioteca definitivo para jugadores de PC y optimizador extremo del sistema.

</div>

Lyra Lazuli Life no es solo un launcher de juegos; es una herramienta integral diseñada para quienes juegan títulos sin soporte de guardado en la nube (DRM-free, repacks, emuladores) y necesitan exprimir hasta el último FPS de su PC.

Combina una interfaz inmersiva estilo consola con un motor de optimización profunda de Windows y un sistema de respaldo automático en Google Drive.

🌟 Características Principales

☁️ Sincronización de Partidas en la Nube

Integración con Google Drive: Respalda tus partidas y metadatos automáticamente. El sistema mantiene un historial rotativo inteligente (Partida actual, de hace 2 días y de hace 4 días).

Vigilante OS (Rastreo en Tiempo Real): ¿No sabes dónde guarda partida un juego? El modo Vigilante monitorea la actividad del disco sin consumir CPU para atrapar el archivo de guardado exacto mientras juegas.

Base de datos oficial (+19,000 juegos): Integra el manifest de Ludusavi para detectar automáticamente las rutas nativas de Windows y emuladores.

🚀 Optimizador Extremo del Sistema (Performance Motor)

El juego se lanza con modificaciones profundas a la API de Windows que se revierten solas al cerrar la aplicación:

Steam Lite: Mata forzosamente los procesos de Steam y lo reinicia en modo ultra-silencioso sin UI, ahorrando cientos de megabytes de RAM.

Zero Input Lag: Usa la API indocumentada NtSetTimerResolution de Windows para forzar el reloj del sistema a 0.5ms.

Modo eSports (Red): Detiene Windows Update, limpia DNS y elimina el límite QoS del 20% reservado por Windows para estabilizar el ping en juegos competitivos.

Smart I/O: Detecta automáticamente si el juego está en un SSD o HDD y ajusta las colas de lectura/escritura (I/O Priority) para evitar stuttering.

AFK Mode GUI: La interfaz de Lyra Lazuli entra en "sueño profundo" (limpiando cachés gráficas y forzando al recolector de basura) para liberar toda la RAM posible mientras juegas.

🎮 Interfaz Inmersiva (Estilo Consola)

Soporte Nativo para Mando: Navega por toda la interfaz, lanza juegos y abre menús usando tu Gamepad.

Overlays Integrados: Presiona ALT+5 (o el botón Home de tu mando) para ver un panel superpuesto con la hora, tiempo de sesión y notificaciones de guardado sin salir del juego.

Scraping Automático: Descarga carátulas, logos transparentes y fondos dinámicos en alta definición desde Steam, GOG, iTunes, Wallhaven y buscadores web.

Diseño Fluido y Personalizable: Efectos de desenfoque (Blur/Mica), música de fondo dinámica, sonidos de interfaz (SFX) y recordatorios de salud.

📥 Descarga y Uso

Lyra Lazuli Life es una aplicación portable (no requiere instalación).

Ve a la sección de Releases (Lanzamientos) en la parte derecha de esta página.

Descarga la versión más reciente del archivo .exe.

Coloca el archivo en una carpeta de tu preferencia (ej. C:\Juegos\Lyra Lazuli Life\).

Haz doble clic para ejecutarlo. ¡El sistema creará automáticamente las carpetas necesarias!

🚨 Configuración de la Nube (Google Drive)

Para que el respaldo en la nube funcione, necesitas usar tu propio acceso a la API de Google Drive (Google Cloud Console):

Habilita la API de Google Drive en Google Cloud Console.

Crea credenciales de escritorio y descarga tu archivo credentials.json.

Coloca el archivo credentials.json en la MISMA CARPETA donde pusiste el archivo .exe.

Al hacer clic en conectar desde la aplicación, se abrirá tu navegador para confirmar el acceso.

⚠️ NOTA DE SEGURIDAD: Mantén tus archivos credentials.json y el token.json (que se generará automáticamente) en privado. Nunca los compartas con nadie.

💬 Soporte y Sugerencias

Si encuentras algún error o tienes ideas para mejorar la aplicación (como nuevas rutas de guardado o ajustes de rendimiento), por favor abre un Issue en la pestaña correspondiente de este repositorio.
