# Infoturno
## _Sistema de control de tiempo Viña Concha y Toro_

Infoturno es un sistema que permite la toma de tiempos en las lineas de produccion de viña concha y toro, dividiendolos en tiempos de preparacion, produccion y tiempos muertos, los cuales a su vez tambien se subdividen.

El sistema, en teoria, estaba pensado para poder obtener resultados mas eficientes en la produccion y atacar los mayores problemas que generaban atrasos en la programacion, separando los tiempos muertos en, por ejemplo, fallas operacionales, ajustes de las maquinas, averias mecanicas, averias electricas, fallas de material, etc.

Junto con mi retiro de Viña Concha y Toro, deje de dar mantenimiento a esta plataforma, por lo que los archivos en este repositorio representan las ultimas versiones hechas y mantenidas por mi.

Archivos que componen el sistema Infoturno:

- Infoturno 7.39.xls
- Infoturno 7.40.xls
- itiempo actual.mdb
- Resumen Linea - General 6-4.xls
- 5Minutos.xls

## Los otros archivos

Los otros archivos contenidos en el repositorio no tienen nada que ver, pero representan una herramienta con la cual se trabajaba en las plantas de produccion (a pesar de tener SAP).

Archivos listados:

- Horas extras 2011 semana xx.xlsm : Archivo para cotejar las horas extras informadas con las horas extras de la plataforma de marcaje.
- Horas roquefort.xlsx : Archivo con el cual la empresa Roquefort informaba sus horas.
- INFO ROQUEFORT.xls : Archivo con el cual la empresa Roquefort le facturaba a Viña Concha y Toro.
- Libro1.xlsx : Archivo con informacion de la base de datos itiempo, no recuerdo la finalidad de este.

## Uso

Infoturno requere de una conexion ODBC para funcionar, en la epoca en que era usado para configurar la conexion se accedia a traves del panel de control - herramientas administrativas - Origenes de datos ODBC, luego se creaba una nueva conexion, indicando que es una base de datos Access, la conexion debe tener el nombre de itiempo, ya que todos los informes y planillas consultaban por este nombre de conexion.

Cabe destacar que dicha base de datos estaba en una unidad de red, la cual por norma estaba conectada al equipo como la unidad z.

Cualquier uso de estos archivos esta permitido, favor no consultar en caso de algun problema ya que no le doy soporte.
