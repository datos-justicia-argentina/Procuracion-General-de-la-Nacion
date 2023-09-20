Procuración General de la Nación - Casos
========================================

En este conjunto de datos se presentan los datos elaborados a partir de datos primarios remitidos por la Procuración General de la Nación, siguiendo el Protocolo Técnico de Datos y de Procesos, en el marco del Convenio Interjurisdiccional de Datos Abiertos de Justicia.

http://datos.jus.gob.ar/dataset/procuracion-general-de-la-nacion-casos

Características
---------------

-   **Fecha de Primera Publicación: 01/11/2019**

-   **Tags o Etiquetas:** Procuración General de la Nación, casos, código penal, delitos, instituciones, justicia federal

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa Justicia Abierta

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa Justicia Abierta

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Política Criminal. Programa Justicia Abierta

-   **Grupo:** Instituciones de Justicia

-   **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Procuración General de la Nación - Casos iniciados - Justicia Federal

-   **Nombre:** pgn-casos-iniciados-justicia-federal.zip

-   **Descripción del contenido:** Contiene los archivos con los datos elaborados a partir de datos primarios remitidos por la Procuración General de la Nación, correspondientes a casos iniciados de la justicia federal.

-   **Formato:** ZIP

-   **Nombre de los archivos contenidos:** pgn-casos-justicia-federal-AAAA.csv

-   **Rango temporal:** casos iniciados en el año AAAA

-   **Observación:** la estructura de los archivos contenidos en este zip está descripta en el recurso "Procuración General de la Nación - Casos iniciados - muestreo"

### Procuración General de la Nación - Casos iniciados - Justicia Federal - Muestreo

-   **Nombre:** pgn-casos-iniciados-justicia-federal-muestreo.csv

-   **Descripción del contenido:** Muestreo de 1000 registros, obtenidos a partir de datos primarios remitidos por la Procuración General de la Nación, correspondientes a casos iniciados de la justicia federal. Los datos completos están publicados en formato zip.

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** muestreo de casos iniciados en el último año informado por la provincia

### Campos del recurso

-   **caso_id (string):** código que identifica el caso

-   **circunscripción_id (string):** identificador de la circunscripción a la que pertenece la unidad en que se inició el caso

-   **circunscripción_descripcion (string):** descripción de la circunscripción a la que pertenece la unidad en que se inició el caso

-   **unidad_id (string):** identificador de la unidad donde se inició el caso

-   **unidad_descripcion (string):** descripción de la unidad en que se inició el caso

-   **caso_fecha_inicio (date):** fecha en que se inició el caso. Tiene el formato AAAA-MM-DD

-   **caso_fecha_hecho (date):** fecha en que se produjo el hecho. Tiene el formato AAAA-MM-DD

-   **caso_hora_hecho (string):** hora en que se produjo el hecho

-   **caso_cantidad_autores_identificados (int):** cantidad numérica total de presuntos autores del hecho, tanto menores como adultos, que fueron denunciados y que han sido identificados

-   **caso_cantidad_autores_no_identificados (int):** cantidad numérica total de presuntos autores del hecho, tanto menores como adultos, que fueron denunciados y que no han sido identificados

-   **caso_cantidad_menores_involucrados_identificados (int):** cantidad numérica de presuntos autores del hecho, que son menores de edad (menores de 18 años)

-   **delito_codigo (string):** código del delito denunciado

-   **delito_descripcion (string):** descripción del delito denunciado

-   **delito_tentativa (string):** indica si el delito se produjo en grado de tentativa. Toma los valores SI/NO

-   **delito_estadistico (string):** agrupación efectuada con fines estadísticos a partir de los delitos informados

-   **fecha_envio (string):** fecha en que la institución remitió el paquete de datos al Ministerio de Justicia y Derechos Humanos de la Nación

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión I](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión III](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-III/blob/main/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Inertjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20III.pdf)

[Código Penal de la Nación Ley - 11.179](http://servicios.infoleg.gob.ar/infolegInternet/anexos/15000-19999/16546/texact.htm)

[Código Procesal Penal de La Nación Ley - 23.984](http://www.saij.gob.ar/23984-nacional-codigo-procesal-penal-lns0003709-1991-08-21/123456789-0abc-defg-g90-73000scanyel)
