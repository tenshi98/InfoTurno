# Infoturno
### _Sistema de control de tiempo Viña Concha y Toro_
Infoturno es un sistema que permite la toma de tiempos en las lineas de produccion de viña concha y toro, dividiendolos en tiempos de preparacion, produccion y tiempos muertos, los cuales a su vez tambien se subdividen.

El sistema, en teoria, estaba pensado para poder obtener resultados mas eficientes en la produccion y atacar los mayores problemas que generaban atrasos en la programacion, separando los tiempos muertos en, por ejemplo, fallas operacionales, ajustes de las maquinas, averias mecanicas, averias electricas, fallas de material, etc.

Junto con mi retiro de Viña Concha y Toro, deje de dar mantenimiento a esta plataforma, por lo que los archivos en este repositorio representan las ultimas versiones hechas y mantenidas por mi.

Archivos que componen el sistema Infoturno:

- Infoturno 7.39.xls
- Infoturno 7.40.xls
- itiempo actual.mdb
- Resumen Linea - General 6-4.xls
- 5Minutos.xls

Sus funciones son las siguientes:

- Infoturno: Plantilla para hacer el ingreso de las detenciones de las lineas de produccion al interior de la planta, este archivo se conecta a una base de datos access a través del servicio de Origenes de bases de Datos (ODBC) del sistema operativo para obtener y guardar los datos.
- Resumen: Informe de analisis gerencial con distintas vistas, donde muestra gráficos por tipo de detenciones, por tipos de cambios, producción por tipo de envase, etc. Este archivo se conecta a una base de datos access a través del servicio de Origenes de bases de Datos (ODBC) del sistema operativo para obtener los datos.
- Resumen Linea: Informe de análisis gerencial, muestra los datos agrupados de distintas formas (tipos de tiempo, tipo de produccion, tipo de enevase, tipo de caja, etc) representado en valores y porcentajes. . Este archivo se conecta a una base de datos access a través del servicio de Origenes de bases de Datos (ODBC) del sistema operativo para obtener los datos.
- Informe 5 Minutos: Informe que permite descargar la información en bruto generada por la plantilla Inforturno, para su posterior uso en la generación de tablas dinámicas y gráficos, este archivo se conecta a una base de datos access a través del servicio de Origenes de bases de Datos (ODBC) del sistema operativo para obtener los datos.

### Los otros archivos

Los otros archivos contenidos en el repositorio no tienen nada que ver, pero representan una herramienta con la cual se trabajaba en las plantas de produccion (a pesar de tener SAP).

Archivos listados:

- Horas extras 2011 semana xx.xlsm : Archivo para cotejar las horas extras informadas con las horas extras de la plataforma de marcaje, este archivo se conecta a una base de datos access a través del servicio de Origenes de bases de Datos (ODBC) del sistema operativo para obtener los datos.
- Horas roquefort.xlsx : Archivo con el cual la empresa Roquefort informaba sus horas.
- INFO ROQUEFORT.xls : Archivo con el cual la empresa Roquefort le facturaba a Viña Concha y Toro.
- Libro1.xlsx : Archivo con informacion de la base de datos itiempo, no recuerdo la finalidad de este.

## Uso 🚀
Infoturno requere de una conexion ODBC para funcionar, en la epoca en que era usado para configurar la conexion se accedia a traves del panel de control - herramientas administrativas - Origenes de datos ODBC, luego se creaba una nueva conexion, indicando que es una base de datos Access, la conexion debe tener el nombre de itiempo, ya que todos los informes y planillas consultaban por este nombre de conexion.

Cabe destacar que dicha base de datos estaba en una unidad de red, la cual por norma estaba conectada al equipo como la unidad z.

Cualquier uso de estos archivos esta permitido, favor no consultar en caso de algun problema ya que no le doy soporte.

## Licencia 📄
Este proyecto está bajo la Licencia GPL-3.0 license - ve el archivo [LICENSE](LICENSE) para detalles

## Contacto 📖
Puedes contactarte conmigo a través de cualquier de los siguientes canales:
- [Github](https://github.com/tenshi98)
- [Linkedin](https://www.linkedin.com/in/victor-reyes-galvez/)
- [Portafolio](https://tenshi98.github.io/portafolio/)
- [Mi Web](https://web.digitalcreations.cl/)

## Contribuciones 🎁
Si encontraste cualquier valor en este proyecto o quieres contribuir, aquí está lo que puedes hacer:

- Comparte este proyecto con otros.
- Invítame un café ☕.
- Inicia un nuevo problema o contribuye con un PR.
- Muestra tu agradecimiento diciendo gracias en un nuevo problema.

---

⌨️ por [Víctor Reyes](https://github.com/tenshi98) 😊
