# Modelos de series de tiempo aplicada a indicadores de género.
  
 
> Material elaborado por [Rocío Piña](https://github.com/rociolopezpi29).  

Realizaremos un ejemplo práctico del análisis de series de tiempo utiizando la información sobre la Tasa de desocupación nacional trimestral publicada por el Instituto Nacional de Estadística y Geografía [(INEGI)](https://www.inegi.org.mx/) y los datos sobre el Tiempo de trabajo no remunerado según ingresos propios por sexo, publicado por el Observatorio de Igualdad de Género de América Latina y el Caribe [(OIG)](https://oig.cepal.org/es). Estas cifras forman parte de los indicadores de genéro sobre autonomía económica. 

### Sobre el material
En la carpeta que se creó para el taller [meetup](https://www.meetup.com/rladies-guadalajara/events/284600941/) del día 26 de marzo de 2022 para [R-Ladies Guadalajara](https://twitter.com/RLadiesGDL), incluye dos archivos de tipo csv y un Rmd:

1. datos_desocupacion.csv
2. data_trabajo_no_remunerado.csv
3. Analisis_de_series_de_tiempo.Rmd


#### Para correr el código es necesario instalar y cargar las siguientes paqueterías:


```
install.packages(c("forecast", "dplyr", "tidyverse",
                    "tseries", "ggfortify" "ggplot2"))
```

![Optional Text](https://pbs.twimg.com/media/FN2hs-xX0AENZY7?format=jpg&name=4096x4096)


#### Package requerida

```
library(dplyr)
library(tidyverse)
library(tseries)     
library(forecast)
library(ggfortify)
library(ggplot2)
```











## Contacto: guadalajara@rladies.com
