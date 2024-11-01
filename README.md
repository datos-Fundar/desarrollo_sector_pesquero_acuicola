# Lorem Ipsum

<!-- CAMBIAR "https://place-hold.it/1920x1080" POR EL LINK A LA IMAGEN CORRESPONDIENTE -->
[![Título del Artículo](https://place-hold.it/1920x1080)](https://fund.ar)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%20NC%20SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
<!-- [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1234.svg)](https://zenodo.org/doi/10.5281/zenodo.11186044) -->

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### Ejemplos de alertas destacadas

> [!NOTE]
> Información importante o útil.

> [!TIP]
> Algún consejo útil a la hora de utilizar este contenido.

> [!IMPORTANT]
> Información clave para usar este repositorio.

> [!WARNING]
> Información urgente para evitar problemas.

> [!CAUTION]
> Potenciales riesgos.

## Ejemplo de código en `R`

```r
datos <- tibble(
  "iso" = c("ARG", "FRA"),
  "2006" = c(2,1),
  "2010" = c(2,1),
  "2014" = c(2,1),
  "2018" = c(2,2),
  "2022" = c(3,2)
)

datos %>% 
  pivot_longer(cols = -iso,
               values_to = "copas", names_to = "anio")
               
```

## Ejemplo de código en `Python`

```python
import seaborn as sns
from run import main, PATHS

empalme_df = main(**PATHS)

# VABpb per capita por provincia 
to_plot = empalme_df.query(expr="provincia != 'No distribuido'") # Solo hay datos entre 2004-2022
anio_max = to_plot.anio.max()
col_ord = to_plot[to_plot.anio==anio_max].sort_values(by='vab_pb_per_capita',ascending=False)['provincia'].to_list()
g =sns.FacetGrid(to_plot, col='provincia', col_wrap=4, col_order=col_ord)
g.map_dataframe(sns.lineplot, x='anio', y='vab_pb_per_capita')
g.set_axis_labels(x_var = "Año", y_var= "Pesos constantes de 2004" )
g.set_titles(col_template="{col_name}")
g.tight_layout()
```

---
<div>&nbsp;</div>
<div>&nbsp;</div>
<div>
  &nbsp;
  <a href="https://fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/6ef27bf9-141f-4537-9d78-e16b80196959">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/aa8e7c72-4fad-403a-a8b9-739724b4c533">
    <img src="fund.ar"></img>
  </picture>
</a>
</div>
