\# NeonBeat 🎵



App Android nativa de reproducción de música local, desarrollada desde cero en Kotlin como proyecto personal. Diseño oscuro con sistema de color neón dinámico, arquitectura MVVM y funcionalidades de nivel producción.



> 🔒 El código fuente es privado — la app está en proceso de publicación en Google Play.



\---



\## Sistema de color neón dinámico



El color neón se aplica a toda la UI en tiempo real: logo, sliders, botones, iconos y minireproductor.



| Naranja | Cyan | Rosa |

|---------|------|------|

| !\[Home Naranja](screenshots/screenshot\_01.jpg) | !\[Home Cyan](screenshots/screenshot\_02.jpg) | !\[Home Rosa](screenshots/screenshot\_03.jpg) |



\---



\## Reproductor



| Reproductor completo | Mini-reproductor | Google Cast en TV |

|---------------------|-----------------|-------------------|

| !\[Player](screenshots/screenshot\_33.jpg) | !\[Mini](screenshots/screenshot\_09.jpg) | !\[Cast TV](screenshots/screenshot\_16.jpg) |



\- Barra de progreso interactiva, shuffle y repeat

\- Mini-reproductor persistente accesible desde cualquier pantalla

\- Carátulas automáticas desde Deezer API, MusicBrainz y Last.fm (fallback en cascada)

\- \*\*Google Cast\*\* — envío de audio a dispositivos Chromecast en la misma red



\---



\## Biblioteca de canciones



| Lista A-Z | Buscador en tiempo real | Menú de opciones |

|-----------|------------------------|-----------------|

| !\[Songs](screenshots/screenshot\_05.jpg) | !\[Search](screenshots/screenshot\_19.jpg) | !\[Menu](screenshots/screenshot\_29.jpg) |



| Editar metadatos | Eliminar canción | Selección múltiple |

|-----------------|-----------------|-------------------|

| !\[Edit](screenshots/screenshot\_21.jpg) | !\[Delete](screenshots/screenshot\_20.jpg) | !\[Multiselect](screenshots/screenshot\_28.jpg) |



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

| !\[Playlists](screenshots/screenshot\_30.jpg) | !\[Playlist detail](screenshots/screenshot\_24.jpg) | !\[Add](screenshots/screenshot\_22.jpg) |



| Nueva playlist | Renombrar | Eliminar playlist |

|---------------|-----------|------------------|

| !\[New](screenshots/screenshot\_31.jpg) | !\[Rename](screenshots/screenshot\_26.jpg) | !\[Delete playlist](screenshots/screenshot\_25.jpg) |



\- Crear, renombrar y eliminar playlists

\- Añadir canciones individualmente o en selección múltiple

\- Eliminar canciones de la lista sin borrar el archivo



\---



\## Ajustes



| Preferencias | Apariencia | Temporizador |

|-------------|-----------|-------------|

| !\[Settings](screenshots/screenshot\_11.jpg) | !\[Appearance](screenshots/screenshot\_12.jpg) | !\[Timer](screenshots/screenshot\_14.jpg) |



| Selector de colores | Reporte de error | Acerca de |

|--------------------|-----------------|-----------|

| !\[Colors](screenshots/screenshot\_13.jpg) | !\[Report](screenshots/screenshot\_10.jpg) | !\[About](screenshots/screenshot\_07.jpg) |



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

