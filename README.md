\# NeonBeat 🎵



App Android nativa de reproducción de música local, desarrollada desde cero en Kotlin como proyecto personal. Diseño oscuro con sistema de color neón dinámico, arquitectura MVVM y funcionalidades de nivel producción.



> 🔒 El código fuente es privado — la app está en proceso de publicación en Google Play.



\---



\## Sistema de color neón dinámico



El color neón se aplica a toda la UI en tiempo real: logo, sliders, botones, iconos y minireproductor.



| Naranja | Cyan | Rosa |

|---------|------|------|

| !\[Home Naranja](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_01.jpeg) | !\[Home Cyan](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_02.jpeg) | !\[Home Rosa](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_03.jpeg) |



\---



\## Reproductor



| Reproductor completo | Mini-reproductor | Google Cast en TV |

|---------------------|-----------------|-------------------|

| !\[Player](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_33.jpeg) | !\[Mini](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_09.jpeg) | !\[Cast TV](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_16.jpeg) |



\- Barra de progreso interactiva, shuffle y repeat

\- Mini-reproductor persistente accesible desde cualquier pantalla

\- Carátulas automáticas desde Deezer API, MusicBrainz y Last.fm (fallback en cascada)

\- \*\*Google Cast\*\* — envío de audio a dispositivos Chromecast en la misma red



\---



\## Biblioteca de canciones



| Lista A-Z | Buscador en tiempo real | Menú de opciones |

|-----------|------------------------|-----------------|

| !\[Songs](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_05.jpeg) | !\[Search](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_19.jpeg) | !\[Menu](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_29.jpeg) |



| Editar metadatos | Eliminar canción | Selección múltiple |

|-----------------|-----------------|-------------------|

| !\[Edit](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_21.jpeg) | !\[Delete](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_20.jpeg) | !\[Multiselect](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_28.jpeg) |



\- Escáner de música local desde el almacenamiento del dispositivo

\- 112+ canciones con carátulas y metadatos

\- Ordenación A-Z

\- Buscador en tiempo real por título o artista

\- Edición de título y artista

\- Selección múltiple para añadir a playlist en masa

\- Eliminación con confirmación



\---



\## Playlists



| Lista de playlists | Detalle de playlist | Añadir a playlist |

|-------------------|--------------------|--------------------|

| !\[Playlists](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_30.jpeg) | !\[Playlist detail](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_24.jpeg) | !\[Add](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_22.jpeg) |



| Nueva playlist | Renombrar | Eliminar playlist |

|---------------|-----------|------------------|

| !\[New](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_31.jpeg) | !\[Rename](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_26.jpeg) | !\[Delete playlist](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_25.jpeg) |



\- Crear, renombrar y eliminar playlists

\- Añadir canciones individualmente o en selección múltiple

\- Eliminar canciones de la lista sin borrar el archivo



\---



\## Ajustes



| Preferencias | Apariencia | Temporizador |

|-------------|-----------|-------------|

| !\[Settings](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_11.jpeg) | !\[Appearance](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_12.jpeg) | !\[Timer](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_14.jpeg) |



| Selector de colores | Reporte de error | Acerca de |

|--------------------|-----------------|-----------|

| !\[Colors](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_13.jpeg) | !\[Report](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_10.jpeg) | !\[About](https://raw.githubusercontent.com/Coprat95/neonbeat-player-public/main/screenshots/screenshot_07.jpeg) |



\*\*Personalización:\*\*

\- 3 temas: Oscuro · Negro · Claro

\- 5 colores neón: Menta · Rosa · Matrix · Fuego · Violeta



\*\*Temporizador de apagado:\*\*

\- Presets: 15 min / 30 min / 1 h

\- Tiempo personalizado en minutos



\---



\## Arquitectura y stack técnico



| Capa | Tecnología |

|------|-----------|

| Lenguaje | Kotlin |

| Arquitectura | MVVM (ViewModel + LiveData) |

| UI | XML layouts · Material Design 3 |

| Audio | MediaPlayer + MediaSession |

| Background | Foreground Service |

| Carátulas | Deezer API · MusicBrainz · Last.fm |

| Cast | Google Cast SDK |

| Preferencias | SharedPreferences + DataStore |

| Persistencia | Room Database |

| Build | Gradle + Kotlin DSL |



\---



\## Autor



\*\*Oliver Travé García\*\*  

Estudiante DAM · ILERNA Barcelona · 2024–2026  

\[LinkedIn](https://www.linkedin.com/in/oliver-travé-garcía-610540209/) · \[GitHub](https://github.com/Coprat95)



\---



> NeonBeat es un proyecto con fines educativos. Las carátulas e información musical se obtienen a través de servicios de terceros (Deezer, MusicBrainz, Last.fm). No nos atribuimos la propiedad ni los derechos de dichos datos.

