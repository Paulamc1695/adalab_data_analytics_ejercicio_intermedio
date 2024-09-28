
## Ejercicio Intermedio del Módulo 3: Transformación de Datos
 
Realización del Ejercicio Intermedio sobre Spotify:

**Los Datos:**

- Varias estadísticas de la versión musical en spotify, incluido el número de streams;
- Número de visualizaciones del vídeo musical oficial de la canción en youtube.

**Las variables que tendremos en este dataframe son:**

Incluye 26 variables para cada una de las canciones recogidas de spotify.

Track: Nombre de la canción tal y como aparece en la plataforma Spotify.

Artist: Nombre del artista.

Url_spotify: URL de la canción en Spotify.

Album: El álbum en el que se encuentra la canción en Spotify.

Album_type: Indica si la canción se publica en Spotify como single o dentro de un álbum.

Uri: Un enlace de Spotify utilizado para encontrar la canción a través de la API.

Danceability: Describe lo adecuada que es una canción para bailar, basándose en una combinación de elementos musicales como el tempo, la estabilidad del ritmo, la fuerza del compás y la regularidad general. Un valor de 0.0 es el menos bailable y 1.0 el más bailable.

Energy: Medida de 0.0 a 1.0 que representa la intensidad y actividad de una canción. Normalmente, las pistas con alta energía son rápidas y ruidosas. Por ejemplo, el death metal tiene mucha energía, mientras que un preludio de Bach tiene una puntuación baja.

Key: La tonalidad de la pista, representada por números enteros utilizando la notación estándar Pitch Class. Por ejemplo, 0 = C, 1 = C♯/D♭, 2 = D, etc. Si no se detecta ninguna tonalidad, el valor es -1.

Loudness: Sonoridad global de una pista en decibelios (dB). Los valores suelen oscilar entre -60 y 0 dB y son útiles para comparar la sonoridad relativa de las pistas.

Speechiness: Detecta la presencia de palabras habladas en una pista. Un valor cercano a 1.0 indica que la grabación es predominantemente hablada, mientras que valores menores representan música no hablada.

Acousticness: Medida de confianza de 0.0 a 1.0 que determina si la pista es acústica. Un valor de 1.0 indica alta confianza en que la pista es acústica.

Instrumentalness: Predice si una pista no contiene voces. Cuanto más se acerque el valor a 1.0, mayor será la probabilidad de que la canción sea instrumental.

Liveness: Detecta la presencia de público en la grabación. Valores más altos indican una mayor probabilidad de que la pista se haya interpretado en directo.

Valence: Medida de 0.0 a 1.0 que describe la positividad musical que transmite una pista. Las pistas con alta valencia suenan más positivas.

Tempo: Tempo global estimado de una pista en pulsaciones por minuto (BPM).

Duration_ms: Duración de la pista en milisegundos.

Stream: Número de reproducciones de la canción en Spotify.

Url_youtube: URL del video enlazado a la canción en YouTube, si lo tiene.

Title: Título del videoclip en YouTube.

Channel: Nombre del canal que ha publicado el video.

Views: Número de vistas del video.

Likes: Número de "me gusta" del video.

Comments: Número de comentarios del video.

Description: Descripción del video en YouTube.

Licensed: Indica si el video representa contenido con licencia, lo que significa que fue subido a un canal vinculado a un socio de contenido de YouTube y luego reclamado por dicho socio.