# NeonBeat 🎵

App Android nativa de reproducción de música local, desarrollada desde cero en Kotlin como proyecto personal. Diseño oscuro con sistema de color neón dinámico, arquitectura MVVM y funcionalidades de nivel producción.

> 🔒 El código fuente es privado — la app está en proceso de publicación en Google Play.

---

## Sistema de color neón dinámico

El color neón se aplica a toda la UI en tiempo real: logo, sliders, botones, iconos y minireproductor.

| Cyan | Rosa | Naranja |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_02.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_03.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_01.jpeg" width="200"/> |

| Selector de tema y color |
|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_13.jpeg" width="200"/> |

---

## Reproductor

| Reproductor completo | Google Cast en TV | Notificación de pantalla de bloqueo |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_33.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_16.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_37.jpeg" width="200"/> |

| Notificación en cualquier fondo |
|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_38.jpeg" width="200"/> |

- Barra de progreso interactiva, shuffle y repeat
- Notificación persistente con controles en pantalla de bloqueo y barra de notificaciones
- Carátulas automáticas desde Deezer API, MusicBrainz y Last.fm (fallback en cascada)
- **Google Cast** — envío de audio a dispositivos Chromecast en la misma red

---

## Biblioteca de canciones

| Lista A-Z | Buscador en tiempo real | Menú de opciones |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_05.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_19.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_29.jpeg" width="200"/> |

| Editar metadatos | Eliminar canción | Selección múltiple |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_21.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_20.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_28.jpeg" width="200"/> |

- 112+ canciones con carátulas y metadatos, ordenación A-Z
- Buscador en tiempo real por título o artista
- Edición de título y artista
- Selección múltiple para añadir a playlist en masa
- Eliminación con confirmación

---

## Playlists

| Lista de playlists | Añadir a playlist | Nueva playlist |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_30.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_22.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_31.jpeg" width="200"/> |

- Crear, renombrar y eliminar playlists
- Añadir canciones individualmente o en selección múltiple
- Reordenación de canciones mediante drag & drop
- Eliminar canciones de la lista sin borrar el archivo

---

## Ajustes

| Preferencias | Selector de colores | Temporizador |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_11.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_13.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_14.jpeg" width="200"/> |

| Reporte de error | Acerca de |
|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_10.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_07.jpeg" width="200"/> |

- 3 temas: Oscuro · Negro · Claro
- 5 colores neón: Menta · Rosa · Matrix · Fuego · Violeta
- Temporizador de apagado con presets (15 min / 30 min / 1 h) y tiempo personalizado
- Reporte de errores por email con información del dispositivo automática

---

## Arquitectura y stack técnico

| Capa | Tecnología |
|---|---|
| Lenguaje | Kotlin |
| Arquitectura | MVVM (ViewModel + LiveData) |
| UI | XML layouts · Material Design 3 |
| Audio | MediaPlayer + MediaSession |
| Background | Foreground Service |
| Carátulas | Deezer API · MusicBrainz · Last.fm |
| Cast | Google Cast SDK |
| Persistencia | Room Database |
| Build | Gradle + Kotlin DSL |

---

## Autor

**Oliver Travé García**  
Estudiante DAM · ILERNA Barcelona · 2024–2026  
[LinkedIn](https://www.linkedin.com/in/oliver-travé-garcía-610540209/) · [GitHub](https://github.com/Coprat95)

> NeonBeat es un proyecto con fines educativos. Las carátulas e información musical se obtienen a través de servicios de terceros. No nos atribuimos la propiedad ni los derechos de dichos datos.
