# Datos para el monitoreo del COVID-19 en México

Los datos sobre el número de casos confirmados, sospechosos y negativos de SARS-COV-2 (COVID-19) en México son publicados por el gobierno a través de la Secretaría de Salud (SSa).

Desde el lunes 13 de abril, la SSa a través de Dirección General de Epidemiología publica [una base de "datos abiertos"](https://www.gob.mx/salud/documentos/datos-abiertos-152127) muy completa y en formato CSV. Desde entonces, este repositorio funciona principalmente como una base de datos (no-oficial) donde se archiva la información actualizada, así como los datos previos publicados en PDF (que han sido archivados, normalizados y convertidos a CSV).

También mantenemos series de tiempo (formato *tidy*) de diferentes variables para facilitar el análisis de la base de datos abiertos.

**Este repositorio es actualizado a diario,** y trabajamos constantemente para mejorarlo. Si tienes algún comentario, queja o sugerencia puedes escribirnos al correo contacto@gmail.com.

Si estás interesado/a en una visualización de los datos que aquí se encuentran, puedes visitar [nuestra página para el monitoreo del coronavirus en México](https://juancruzd.github.io/mexicovid19/index.html) .


## Datos

1. Datos abiertos:
    - [datos_abiertos/raw](datos_abiertos/raw): los datos publicados por la DGE a partir del lunes 13 de abril.

2. Datos abiertos en formato *tidy*:
    - [datos_abiertos/series_de_tiempo/nuevos](datos_abiertos/series_de_tiempo/nuevos):
    diferentes variables contabilizadas por día y por estado.
    - [datos_abiertos/series_de_tiempo/acumulados](datos_abiertos/series_de_tiempo/acumulados):
    diferentes variables contabilizadas por día y por estado y acumuladas hasta la fecha más reciente.

3. Datos correspondientes a formatos antiguos (PDFs, SINAVE) y publicados hasta el 19 de abril (SSa ha dejado de actualizarlos):
    - [datos/reportes_oficiales_ssa](datos/reportes_oficiales_ssa): se archivan las tablas de confirmados y sospechosos en formato CSV generadas a partir de los archivos PDF que SSa publicaba.
    - [datos/sinave](datos/sinave): se archivan los datos en formato JSON que se extraían  del mapa de SINAVE.

4. Datos correspondientes a formatos antiguos en formato *tidy*:
    - [datos/series_de_tiempo](datos/series_de_tiempo): el historial de casos a nivel nacional y desglosados por estado. **Estas series de tiempo se siguen actualizando con la base de datos abiertos** (el total de casos confirmados se asocia con el día de publicación).
 

## Fuentes para los datos del COVID-19

- [Datos abiertos de la Dirección General de Epidemiología](https://www.gob.mx/salud/documentos/datos-abiertos-152127) publicados por la Secretaría de Salud Federal. Estos datos has sido publicados con una licencia `Libre Uso MX` como consta en el [portal de datos abiertos del gobierno](https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico). 

Ya no se actualiza con casos confirmados, negativos o sospechosos (solo con casos activos).




Otras fuentes que **no se incluyen aquí**

- [Serendipia - Periodismo de datos](https://serendipia.digital/2020/03/datos-abiertos-sobre-casos-de-coronavirus-covid-19-en-mexico/)
- [Blog de @mayrop](https://www.covid19in.mx/docs/datos/tablas-casos/)
- [Our World in Data](https://ourworldindata.org/coronavirus)
- [Worldometers](https://www.worldometers.info/coronavirus/country/mexico/): reporta casos recuperados pero no menciona la fuente.
- [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19): para México reporta como fuente a Worldometers
- [IIGEA](iigea.com/amag/covid-19/): recopila información de las Secretarías Estatales de Salud.
- [verificovid](https://verificovid.mx/);
 
 
### Otros datos

- Población y número promedio de familia por estados, 2015: [Inegi, Encuesta Intercensal 2015](https://www.inegi.org.mx/programas/intercensal/2015/default.html#Tabulados);

- Polígonos de los estados del país en formato GEOJSON: [Blocks](http://bl.ocks.org/ponentesincausa/46d1d9a94ca04a56f93d)

 