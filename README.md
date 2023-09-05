# COVID-19-Confirmed-Cases-Analysis
###### Find the English version of this README file in the main branch of this project
A partir de un proyecto guiado en Coursera hace ya casi 3 años, he decidido retomar el análisis y agregarle algunas preguntas de mi autoría que me fueron surgiendo, a partir de mi curiosidad de conocer cómo fue la situación de mi país Ecuador durante la pandemia. *Proyecto en desarrollo

## Datos técnicos
### Acerca del dataset
Para el proyecto, utilicé datos de casos totales diarios confirmados de COVID 19 de Enero 22 a Abril 30 del 2020; de todos los países a nivel mundial, en formato csv (Disponible en este repositorio); obtenido de Coursera Project Network
### Acerca del lenguaje y entorno
Se usó el entorno de Jupyter Labs en Anaconda para el despliegue del análisis; con Python como lenguaje de programación. Archivo en formato .iypnb
Librerías usadas: numpy, pandas, seaborn, matplotlib, plotly, datetime, calendar

## ¿Qué quiero saber con este análisis?
Quise orientar este análisis a la situación de Ecuador durante los primeros meses de la pandemia, queriendo identificar:
- La evolución de casos diarios totales confirmados de enero a abril
- La evolución de casos nuevos en 24h confirmados en el mismo periódo
- Cómo se compara la tasa de infección diaria de Ecuador con otros países de América Latina
- Cómo se compara este mismo parámetro con otros países a nivel mundial.
- El top 10 de países que registraron el mayor número de nuevos contagiados en 24h a nivel mundial
- Datos adicionales sobre cúanto y cúando ocurrió ese pico de contagios para un país en particular.

## Hallazgos importantes
- Confirmando lo reportado en noticieros locales, los primeros casos confirmados de COVID 19 en Ecuador, Argentina y Brasil empezaron a reportarse a finales de febrero y a inicios de marzo del 2020. Por unos cuantos días, Ecuador incluso supera en número de casos confirmados a Brasil, a pesar de que este último país reportó sus primeros casos antes. Este hallazgo apoya lo reportado en esos días a nivel nacional: Ecuador estaba teniendo graves problemas con el sistema de salud para atender la pandemia, y los contagios se empezaron a salir de control muy rápido.
<p align="center">
  <img src= "https://github.com/Karen-Benites/COVID-19-Confirmed-cases-analysis/blob/main/Pictures/Confirmed%20cases%20over%20time%20for%20three%20countries.png">
</p>
- Comparando la tasa de infección diaria de los mismos 3 países, vemos que Brasil tiene un crecimiento sostenido y muy alto de contagios diarios en comparación con Ecuador y Argentina; a excepción de un día en Abril del 2020; en donde Ecuador sobrepasó con creces a los otros dos países en número de nuevos contagiados en un sólo día. Esto me llamó la atención; ya que es la segunda vez que veo un comportamiento destacable para mi país en comparación con otros países de América Latina. Esto me llevó a querer ver la evolución de casos confirmados en otros países a nivel mundial y compararlo con Ecuador.

#### La tragedia vivida en Ecuador durante los primeros meses de pandemia
- Lo que empezó con una simple pregunta curiosa; terminó por hallar resultados sorprendentes para mí. Ese pico de nuevos contagiados en un sólo día en Ecuador, no sólo era uno de los más altos de la región; si no que también lo fue a nivel mundial. Sobrepasando incluso a países Europeos como España, UK, y a Brasil en América Latina; ahora tiene sentido el por qué fuimos portada de noticias a nivel internacional en esos oscuros días de pandemia. Los recuerdos de decenas de personas muriendo súbditamente en las calles, cada día reportándose miles de nuevos contagios; fue un evento traumático para el país, y símbolo de la ineficiencia total del sistema de salud; que colapsó rápidamente ante esta inesperada situación. Datos como estos nos lleva a una importante reflexión sobre la necesidad de invertir en el sistema de salud público; y evitar en el futuro tragedias similares.

## ¿Qué sigue próximamente?
Deseo expandir aún más este análisis que hice; añadiendo los siguientes elementos:
- Comparación con otros factores como: índices de felicidad por país, su GDP per cápita, etc.
- Comparación de número de casos confirmados totales diarios con el número de muertes confirmadas diarias, y ver qué tanto cambia el top 10 a nivel global

###### *Estos análisis extras están en proceso. Se actualizarán muy pronto😁
