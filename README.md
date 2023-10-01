# CABA_ECOBICI

![Alt desc](https://github.com/Longchamps27/CABA_ECOBICI/blob/main/Imagenes/ECOBICI.jpg)

ECOBICI es un sistema de bicicletas compartidas en la Ciudad de Buenos Aires con el fín de fomentar el uso de bicicletas como medio de transporte. En 2019 el sistema fue vendido a la empresa Tembici y durante parte del 2020 el sistema fue suspendido debido a la pandemia de COVID-19. Debido a que no hay información de como se vio afectado el servició durante este período de transición, decidí analizarlo y vizualisar la data mediante un dashboard.<br />

El trabajo fue guardado en mi cuenta pública de Tableau: https://public.tableau.com/app/profile/emiliano.blanco5974/viz/CABA_Bicis_Analisis/CABAECOBICIS

# ANALISIS

Diseñé las visualizaciones para exponer el análisis de la base de datos. Trabaje con el espacio de tiempo 2019 - Julio 2023.

Las siguientes son varias de las preguntas que elegí responder:

* ¿Cuáles son las 10 estaciones más y menos usadas para iniciar un viaje?
* ¿Cuáles son las 10 estaciones más y menos usadas para terminar un viaje?
* ¿Cómo varía el uso de las ECOBICIS a lo largo del año?
* ¿Cuáles son las horas picos de uso de las ECOBICIS?
* ¿Cómo cambió el uso de las ECOBICIS en los años posteriores a la compra del sistema y a la pandemia COVID-19?

# PROBLEMAS ENCONTRADOS

La data no estaba organizada de manera limpia y consistente, lo que dificultaba su analisis. <br />
Utilizando Python en Jupyter Notebook, limpié los valores nulos, mal subidos o inconsistentes y fusioné los dataframes
de cada año en uno que abarcaba desde el año 2019 hasta Julio de 2023.
