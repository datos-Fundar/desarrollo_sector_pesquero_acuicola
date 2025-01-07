# Descripción de archivos de datos

Este repositorio contiene una serie de archivos de datos en formato .csv utilizados en el documento [Aprovechar el viento a favor. Oportunidades para el desarrollo del sector pesquero y acuícola en Argentina](https://fund.ar/publicacion/aprovechar-el-viento-a-favor-oportunidades-para-el-desarrollo-del-sector-pesquero-y-acuicola/). Cada archivo corresponde a una tabla específica con información relevante sobre la producción, exportación, empleo y otros aspectos del sector. A continuación, se ofrece una breve descripción de cada archivo y sus columnas, junto con el tipo de datos para facilitar la comprensión y el análisis de los mismos.

## Archivos .csv y descripción de campos

### pesca_marina_paises.csv
- **País o territorio**: Nombre del país o territorio (texto)
- **Decenio de 1980 a 2020**: Producción en pesca marina por década (númerico)
- **Porcentaje del total (2020)**: Porcentaje total para el año 2020 (númerico)

### pesca_continental_paises.csv
- **País**: Nombre del país (texto)
- **Decenio de 1980 a 2020**: Producción en pesca continental por década (texto/número)
- **Porcentaje del total (2020)**: Porcentaje total para el año 2020 (texto)

### evolucion_produccion_mundial.csv
- **Entity**: Nombre del país o región (texto)
- **Año**: Año del dato (entero)
- **Acuicultura**: Producción en acuicultura (entero)
- **Pesca de captura**: Producción en pesca de captura (entero)
- **Total**: Total de producción (entero)

### exportaciones_por_sectores.csv
- **Complejo pesquero, Complejo carnes (bovino), Total exportaciones**: Valores de exportación en millones de USD(entero)

### evolucion_exportaciones_pesqueras.csv
- **Año**: Año de la observación (entero)
- **Merluza hubbsi**: Cantidad exportada de Merluza hubbsi en toneladas (decimal)
- **Langostino**: Cantidad exportada de Langostino en toneladas (entero)
- **Calamar**: Cantidad exportada de Calamar en toneladas (entero)
- **Otras especies**: Cantidad exportada de otras especies en toneladas (decimal)
- **Millones de dolares**: Valor total de las exportaciones en millones de dólares (entero)
- **Toneladas**: Peso total exportado en toneladas (entero)
- **Precio promedio**: Precio promedio de exportación en dólares por tonelada (decimal)

### produccion_acuicultura_argentina.csv
- **Entity**: Nombre del país o región (texto)
- **Año**: Año de producción (entero)
- **Producción acuícola**: Producción en acuicultura (decimal)

### evolucion_empleo_registrado.csv
- **Año**: Año de registro (entero)
- **Pesca y recolección, Acuicultura, Servicios, Elaboración y procesamiento**: Cantidad de empleos en cada sector (decimal)

### empleo_OEDE.csv
- **Rama de actividad**: Nombre del sector de actividad (texto)
- **Remuneración (pesos)**: Promedio de remuneración en pesos (entero)

### evolucion_desembarques_puertos.csv
- **Buenos Aires, Rio Negro, Chubut, Santa Cruz, Tierra del Fuego, Otros puertos**: Desembarques en toneladas (decimal)

### evolucion_capturas_marinas.csv
- **Año**: Año del dato (entero)
- **Capturas marinas**: Cantidad de capturas en toneladas (entero)

### capturas_maximas_permisibles.csv
- **Año**: Año del dato (entero)
- **Merluza, Norte, Sur**: Capturas máximas permisibles en diferentes áreas (decimal)
- **CMP total**: Captura máxima permisible total (decimal)
- **Captura Total**: Total de capturas (decimal)

### evolucion_desembarques_por_especie.csv
- **Año**: Año del dato (entero)
- **Peces, Crustáceos, Moluscos**: Desembarques en toneladas para cada grupo (decimal)

### evolucion_exportaciones.csv
- **Evolución exportaciones pesqueras en millones de dólares**: Valores de exportación (decimal)

### evolucion_precios_internacionales.csv
- **Merluza hubbsi, Langostino, Calamar**: Precios internacionales de exportación en dólares (entero)

### evolucion_desembarques_segun.csv
- **Año**: Año de la observación (entero)
- **Fresqueros**:
  - **Rada o Ria**: Desembarques de fresqueros en rada o ría (decimal)
  - **Costeros**: Desembarques de fresqueros costeros (decimal)
  - **Fresqueros altura**: Desembarques de fresqueros de altura (decimal)
  - **Subtotal fresqueros**: Total de desembarques fresqueros (decimal)
- **Congeladores**:
  - **Arrastreros**: Desembarques de congeladores arrastreros (decimal)
  - **Palangreros**: Desembarques de congeladores palangreros (decimal)
  - **Tangoneros**: Desembarques de congeladores tangoneros (decimal)
  - **Surimeros**: Desembarques de congeladores surimeros (decimal)
  - **Poteros Charteados**: Desembarques de poteros charteados (decimal)
  - **Poteros Nacionales**: Desembarques de poteros nacionales (decimal)
  - **Poteros totales**: Total de desembarques de poteros (decimal)
  - **Tramperos**: Desembarques de tramperos (decimal)
  - **Otras artes**: Desembarques de otras artes de pesca (decimal)
  - **Subtotal congeladores**: Total de desembarques de congeladores (decimal)
- **Total**: Total de desembarques sumando fresqueros y congeladores (decimal)

