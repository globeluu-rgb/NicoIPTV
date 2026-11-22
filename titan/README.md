NICO IPTV - prototipo Titan OS 0.2

Aplicación web HTML5 independiente de la versión Android/Fire TV.

MEJORAS 0.2
- Navegación por foco con las flechas del mando.
- Cambio de canal con Channel Up/Down, Page Up/Down y teclas multimedia.
- Reproducción de temporadas y episodios de series.
- EPG actual y siguiente cuando el servidor lo facilita.
- Intento automático HLS (.m3u8) y alternativa TS para TV en directo.
- Pantalla completa compatible con requestFullscreen y webkitRequestFullscreen.
- Diagnóstico visible de CORS, contenido mixto HTTP/HTTPS y códecs.
- Las credenciales solo viven durante la sesión y se borran al salir.

PRUEBA EN PHILIPS TITAN OS
1. Alojar index.html en una URL web.
2. Registrar esa URL en el entorno de pruebas de Titan/DevView.
3. Vincular el televisor Philips con DevView y abrir la aplicación.
4. Probar login, mando, TV en directo, películas, series, audio y pantalla completa.

IMPORTANTE
- No es un APK. Titan OS ejecuta una aplicación web.
- Si la página se aloja con HTTPS pero el servidor Xtream solo ofrece HTTP, el
  motor del televisor puede bloquear la conexión por contenido mixto.
- La reproducción final depende de CORS, códecs y formatos admitidos por el
  modelo concreto del televisor.
- Usar únicamente servicios y contenidos autorizados.
