MINES & ROULETTE AI PRO — VERSIÓN 1.0
=====================================

QUÉ INCLUYE
- Interfaz web móvil con estética oscura.
- Simulador de ruleta europea (0–36), con número, rojo/negro, par/impar y mitades.
- Simulador Mines 5x5 con 3, 5, 7, 10, 15, 20 o 24 minas.
- Confirmación manual antes de cada apuesta virtual y antes de cobrar.
- Saldo virtual de $1,000, historial, estadísticas y exportación CSV.
- PWA básica para instalación como aplicación web y caché offline una vez servida.
- No requiere cuenta ni API y no utiliza dinero real.

IMPORTANTE
Este es un simulador educativo. No se conecta a casinos, no lee juegos de terceros, no coloca apuestas reales y no predice resultados. La selección de resultados y minas es aleatoria. No hay garantía de ganancias.

PROBAR DIRECTAMENTE EN ANDROID
1. Descarga y extrae el ZIP en tu teléfono.
2. Abre index.html desde un administrador de archivos o editor HTML con vista previa.
3. Prueba Ruleta: selecciona tipo y cantidad, pulsa “Confirmar apuesta y girar” y confirma.
4. Prueba Mines: pulsa “Confirmar e iniciar”, confirma, abre una casilla y pulsa “Cobrar ahora” si quieres cobrar.
5. Abre Estadísticas, comprueba el historial y prueba “Exportar historial CSV”.
Nota: algunas vistas previas locales no permiten instalar la PWA ni usar service worker. Para esas funciones hace falta servir los archivos por HTTPS.

INSTALAR COMO APP DESDE ANDROID (SIN ORDENADOR)
Método recomendado: publicar los archivos en un hosting HTTPS compatible y usar “Añadir a pantalla de inicio” en Chrome.
1. Sube index.html, manifest.webmanifest y sw.js a un hosting estático HTTPS de tu elección.
2. Abre la URL publicada en Chrome para Android.
3. Menú ⋮ > “Añadir a pantalla de inicio” o “Instalar aplicación”, si aparece.
Esto crea una app web instalable, no un APK nativo.

PARA OBTENER APK
Para generar un APK real necesitas un servicio de compilación Android/PWA compatible o un entorno de desarrollo Android. Desde el teléfono puedes usar una plataforma web de compilación PWA a APK; revisa cuidadosamente permisos, privacidad y firma antes de instalar. Este ZIP por sí solo no es un APK y no debe confundirse con uno. No subas credenciales de casino a servicios de terceros.

PRUEBAS RÁPIDAS
- Ruleta: número exacto solo gana si coincide; paga 35:1 más devolución de la apuesta (pago total 36x).
- Ruleta: rojo/negro, par/impar y mitades pagan 1:1 más devolución de la apuesta.
- El 0 no gana en apuestas externas (rojo/negro, par/impar, 1–18, 19–36).
- Mines: una mina termina la partida y pierde la apuesta virtual; una casilla segura actualiza el multiplicador.
- Cobro: solo está habilitado después de descubrir al menos una casilla segura.
- Estadísticas: reflejan resultados de la sesión actual; el historial se exporta a CSV.
- Reiniciar devuelve saldo a $1,000 y elimina el historial local de la sesión.

LIMITACIONES CONOCIDAS
- El historial se mantiene en memoria mientras la página está abierta; no se garantiza conservarlo al cerrar o recargar.
- No hay IA predictiva real: los consejos son descriptivos y no conocen resultados futuros.
- No incluye autenticación, servidor, sincronización ni conexión con plataformas de juego.
