# Entrega 2 Benjamín Chávez

## El tema central de nuestro trabajo, es hallar las causas y factores que hicieron que el Partido de la Gente -un partido que en 2021, tras su constitución en el mes de julio, logró atraer a 46.138 afiliados-, reconocido por su líder Franco Parisi, iniciara un declive tanto en relevancia a nivel político nacional, como en la afectación de su credibilidad.

## Los datos que utilicé son estadísticas de afiliados al PDG en 2024 por sexo y región, total de afiliados en Chile por sexo y región a todos los partidos políticos existentes (para tener en cuenta en que % se encuentra el PDG), y una base de datos propia elaborada a partir del cálculo del porcentaje entre ambas estadísticas previas, para tener el % específico de afiliados al PDG según su sexo por cada una de las regiones de Chile en 2024.

## La limpieza de datos la hice recopilando en un documento de Drive las estadísticas oficiales de Servel (a las de años anteriores accedí gracias a Wayback Machine). Posteriormente las organicé e imprimí con lenguaje Python en la herramienta de Google Colab para emplear filtros de limpieza. Por último hice el comit respectivo, y me aseguré de compilarlos en un archivo 'csv' a parte.

## Con mis datos, espero responder a las siguientes preguntas sobre el PDG: 
### 1. ¿Por qué hay regiones específicas en las que existe, a 2024, mayor apoyo hacia el PDG?
### 2. ¿Qué tipo de factores socio-políticos, económicos o sociales podrían tener que ver con este apoyo regional?
### 3. ¿Por qué la cantidad de afiliados en la Región Metropolitana es considerablemente menor, si es la región más poblada de Chile?

#### Fuentes usadas: Servel, de momento (se espera conseguir cifras directas de parte del PDG)

## Codificación de las variables: 
### 1. Característica de los datos: Cuantitativos discretos (en el caso de las dos primeras bases), y continuas en el caso de la tercera base.
### 2. Alcance metodológico: Es un estudio sobre un partido específico, pero con representación en todas las regiones, considerando afiliados y sus procentajes en cada una de estas.
### 3. Variables incorporadas (variable | descripción): Las tres bases usan las variables 'sexo' (femenino masculino) y 'región' (las de nuestro país), además de 'afiliados' totales y por cada una de estas. 
### 4. Observaciones que tengan sobre la base de datos: Las tres bases de datos están hechas en base a estadísticas e información proporcionada por Servel. Se intentó acceder a otras estadísticas como presupuesto, por ejemplo, pero la solicitud vía mecanismo de transparencia requiere un trámite de 1 mes. Se intentará conseguir mayor variación en cuanto a datos y variables. 
