# EDA & Data Wrangling

_Colección de ejercicios prácticos de Análisis Exploratorio de Datos (EDA) y Data Wrangling._

_Técnicas de limpieza, transformación y visualización para convertir datos crudos en historias con sentido._

<table style="width: 100%; border-collapse: collapse;">
 
 <tr>
  <td align="center" valign="middle" width="20%" style="padding: 10px; border: 1px solid #ccc;">
    <a href="https://colab.research.google.com/drive/1tRJxv8AKgQoX_Jn7Aw7MYQKb5KHVEK5P?authuser=3" target="_blank">
      <img src="https://lh3.googleusercontent.com/d/1wiw7jXxYWcuGnh0FXgQhvEvNG67vUIdI"
           alt="IMDb" 
           style="max-width: 100%; height: auto; display: block;">
     <img src="https://img.shields.io/badge/Colab-Python-blue?logo=googlecolab" alt="Colab">
    </a>
  </td>
    <td align="left" valign="top" width="80%" style="padding: 20px; border: 1px solid #ccc;">
      <h3>IMDb Insights: Limpieza de Datos y Análisis Exploratorio del Top 1000 Cinematográfico </h3>
      <p>Este análisis demuestra cómo la normalización previa del dataset permite consultas de alto nivel sin errores de duplicidad.</p><br>
      <b>Habiliades:</b> <code>ETL</code> <code>Python</code> <code>Pandas</code> <code>Matplotlib</code> <code>Numpy</code> <code>One-Hot Encoding</code>
      <br><br>
  <ul>
    <p>El EDA final identifica a los directores clave que definen el Top 1000 de IMDb. Mediante el uso de <code>groupby</code> y funciones de agregación, determinamos: </p>
        <li><b>Impacto Financiero:</b> Identificación de los 10 directores con mayor recaudación acumulada, destacando la relación entre grandes presupuestos y éxito comercial.</li>
        <li><b>Consistencia Crítica:</b> Filtrado de directores con múltiples obras (n > 3) para evaluar la calidad sostenida mediante el <code>rating</code> promedio.</li>
    </ul>
    <br>
     <h3>Se puede consultar el código aqui:</h3>
    <a href="https://colab.research.google.com/drive/1tRJxv8AKgQoX_Jn7Aw7MYQKb5KHVEK5P?authuser=3" target="_blank">
      <img src="https://img.shields.io/badge/Colab-Python-blue?logo=googlecolab" alt="Colab">
    </a>
  </td>
</tr>

<tr>
  <td align="center" valign="middle" width="20%" style="padding: 10px; border: 1px solid #ccc;">
    <a href="#" target="_blank">
      <img src="https://lh3.googleusercontent.com/d/1Nf2ne_5V5mmWgGvrStJF0oSN2K5PKNFV"        
           alt="Spotify Data Visualization" 
           style="max-width: 100%; height: auto; display: block;">
    </a>
  </td>
  <td align="left" valign="top" width="80%" style="padding: 20px; border: 1px solid #ccc;">
    <h3>Spotify Tracks Analysis</h3>
    <p>Análisis detallado de tendencias musicales utilizando Python. Exploración de métricas de popularidad, géneros y características de audio.</p>
    <b>Habilidades:</b> <code>ETL</code> <code>Python</code> <code>Pandas</code> <code>Matplotlib</code>
    <br><br>
    <ul>
      <p>El análisis estadístico revela un dataset con una fuerte inclinación hacia la música comercial moderna: </p>
      <li><b>Perfil Sonoro:</b> Predominancia de temas con alta <code>energy</code> (avg 0.64) y baja <code>instrumentalness</code>, indicando contenido mayoritariamente vocal.</li>
      <li><b>Popularidad:</b> Existe un sesgo hacia valores bajos; el 50% de las pistas tiene una popularidad inferior a 35 puntos.</li>
      <li><b>Ritmo:</b> El <code>tempo</code> promedio de 122 BPM y el compás de 4/4 sugieren una base de datos centrada en géneros contemporáneos como Pop, Dance o Rock.</li>
    </ul>
    <br>
     <h3>Se puede consultar el código aqui:</h3>
    <a href="https://colab.research.google.com/drive/17_41ZhhfB1XsPMK6f6PSZfJWbwE96DoW?usp=sharing" target="_blank">
      <img src="https://img.shields.io/badge/Colab-Python-blue?logo=googlecolab" alt="Colab">
    </a>

<tr>
  <td align="center" valign="middle" width="20%" style="padding: 10px; border: 1px solid #ccc;">
    <a href="#" target="_blank">
      <img src="https://lh3.googleusercontent.com/d/1ybcD-fahvDhiV7aDhhxRZI91N7UYJUPc"        
           alt="Spotify Data Visualization" 
           style="max-width: 100%; height: auto; display: block;">
    </a>
  </td>
  <td align="left" valign="top" width="80%" style="padding: 20px; border: 1px solid #ccc;">
    <h3>Preferencias musicales en las ciudades de Springfield y Shelbyville </h3>
    <p>Análisis estadístico sobre +60k registros para identificar patrones de escucha urbanos. Implementación de pruebas Chi-cuadrado para validación de segmentación geográfica.</p>
    <b>Habilidades:</b> <code>Python</code> <code>Pandas</code> <code>scipy</code> <code>matplotlib</code> <code>seaborn</code> <code>google.colab</code>
    <br><br>
    <ul>
      <p>Hipotesis: comparar el coportamiento de los usuarios en dos ciudades:</p>
      <li><b>Hipótesis Nula <code>H0</code>:</b> El consumo de géneros es independiente de la ciudad</li>
      <li><b>Conclusión: </b>La disparidad en las preferencias de géneros (notablemente en Pop, Rock y World) no es producto del azar, lo que valida la necesidad de modelos de recomendación geolocalizados. El estadístico $\chi^2$ de 178.53 confirma una fuerte dependencia entre las variables categóricas analizadas.</li>
    </ul>
    <br>
     <h3>Se puede consultar el código aqui:</h3>
    <a href="https://colab.research.google.com/drive/1EDb87lnDk32qi5Xl1b2iD30IK_ezJ4-3?usp=drive_link" target="_blank">
      <img src="https://img.shields.io/badge/Colab-Python-blue?logo=googlecolab" alt="Colab">
    </a>   
  </td>
</tr>
