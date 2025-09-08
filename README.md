# P P1. Regresión

Para este proyecto se utilizará la base de datos **Spotify Tracks Dataset** del autor Maharshi Pandya, la cual se encuentra disponible en este [link](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset/data). De acuerdo con su descripción, el conjunto de datos incluye canciones de aproximadamente 125 géneros musicales, junto con diversas características relacionadas con sus propiedades de audio. El objetivo de este proyecto es determinar la **popularidad de una canción de pop** a partir de dichas características.

A continuación se explicarán las variables encontradas en la base de datos *spotifydataset.csv*:
- **Unnamed: 0** → funge como numeración de los datos  
- **track_id** → clave para identificar la canción en Spotify  
- **artists** → artista o artistas que interpretan la canción  
- **album_name** → nombre del álbum donde se encuentra la canción  
- **track_name** → nombre de la canción
- **popularity** → Popularidad de la canción, medida del 0 al 100 (100 es lo más popular). Se calcula mediante un algoritmo que considera principalmente el número total de reproducciones y qué tan recientes han sido dichas reproducciones. (Respuesta de interés)
- **duration_ms** → Duración de la canción en milisegundos.
- **explicit** → Indica si la canción contiene letra explícita (`true` = sí, `false` = no).
- **danceability** → Mide qué tan bailable es una canción (0.0 a 1.0) considerando elementos como tempo, estabilidad del ritmo, fuerza del beat y regularidad general.
- **energy** → Nivel de energía de la canción (0.0 a 1.0). Representa intensidad y actividad perceptual. 
- **key** → Tono de la canción representado como un número entero. Ejemplo: 0 = C, 1 = C♯/D♭, 2 = D, etc.
- **loudness** → Nivel general de volumen de la canción en decibeles (dB).
- **mode** → Indica la modalidad de la canción: mayor (`1`) o menor (`0`).
- **speechiness** → Detecta la presencia de palabras habladas en una canción (0.0 a 1.0).    
- **acousticness** → Confianza (0.0 a 1.0) de que una canción es acústica. Un valor cercano a 1 indica alta probabilidad de serlo.
- **instrumentalness** → Predice si una canción carece de voces (0.0 a 1.0). Valores cercanos a 1 sugieren que la canción es instrumental.
- **liveness** → Estima la presencia de audiencia en la grabación (0.0 a 1.0). Valores superiores a 0.8 indican fuerte probabilidad de que sea una interpretación en vivo.
- **valence** → Mide la positividad emocional de la canción (0.0 a 1.0). Valores altos reflejan emociones positivas (felicidad, euforia), mientras que valores bajos reflejan emociones negativas (tristeza, enojo).
- **tempo** → Tempo estimado de la canción en beats per minute (BPM).
- **time_signature** → Compás estimado de la canción, es decir, cuántos tiempos hay en cada barra. Toma valores enteros entre 3 y 7 (ej. 3/4, 4/4, 7/4).
- **track_genre** → Género musical al que pertenece la canción.
