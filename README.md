Readme · MDCopiarNeonBeat 🎵
App Android nativa de reproducción de música local, desarrollada desde cero en Kotlin como proyecto personal. Diseño oscuro con sistema de color neón dinámico, arquitectura MVVM y funcionalidades de nivel producción.

🔒 El código fuente es privado — la app está en proceso de publicación en Google Play.


Sistema de color neón dinámico
El color neón se aplica a toda la UI en tiempo real: logo, sliders, botones, iconos y minireproductor.
NaranjaCyanRosaMostrar imagenMostrar imagenMostrar imagen

Reproductor
Reproductor completoMini-reproductorGoogle Cast en TVMostrar imagenMostrar imagenMostrar imagen

Barra de progreso interactiva, shuffle y repeat
Mini-reproductor persistente accesible desde cualquier pantalla
Carátulas automáticas desde Deezer API, MusicBrainz y Last.fm (fallback en cascada)
Google Cast — envío de audio a dispositivos Chromecast en la misma red


Biblioteca de canciones
Lista A-ZBuscador en tiempo realMenú de opcionesMostrar imagenMostrar imagenMostrar imagen
Editar metadatosEliminar canciónSelección múltipleMostrar imagenMostrar imagenMostrar imagen

Escáner de música local desde el almacenamiento del dispositivo
112+ canciones con carátulas y metadatos
Ordenación A-Z
Buscador en tiempo real por título o artista
Edición de título y artista
Selección múltiple para añadir a playlist en masa
Eliminación con confirmación


Playlists
Lista de playlistsDetalle de playlistAñadir a playlistMostrar imagenMostrar imagenMostrar imagen
Nueva playlistRenombrarEliminar playlistMostrar imagenMostrar imagenMostrar imagen

Crear, renombrar y eliminar playlists
Añadir canciones individualmente o en selección múltiple
Eliminar canciones de la lista sin borrar el archivo


Ajustes
PreferenciasAparienciaTemporizadorMostrar imagenMostrar imagenMostrar imagen
Selector de coloresReporte de errorAcerca deMostrar imagenMostrar imagenMostrar imagen
Personalización:

3 temas: Oscuro · Negro · Claro
5 colores neón: Menta · Rosa · Matrix · Fuego · Violeta

Temporizador de apagado:

Presets: 15 min / 30 min / 1 h
Tiempo personalizado en minutos


Arquitectura y stack técnico
CapaTecnologíaLenguajeKotlinArquitecturaMVVM (ViewModel + LiveData)UIXML layouts · Material Design 3AudioMediaPlayer + MediaSessionBackgroundForeground ServiceCarátulasDeezer API · MusicBrainz · Last.fmCastGoogle Cast SDKPreferenciasSharedPreferences + DataStorePersistenciaRoom DatabaseBuildGradle + Kotlin DSL

Autor
Oliver Travé García
Estudiante DAM · ILERNA Barcelona · 2024–2026
LinkedIn · GitHub


NeonBeat es un proyecto con fines educativos. Las carátulas e información musical se obtienen a través de servicios de terceros (Deezer, MusicBrainz, Last.fm). No nos atribuimos la propiedad ni los derechos de dichos datos.
