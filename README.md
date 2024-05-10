# Supertienda-Power-BI


<img src="https://github.com/Bearodriguez2022/Supertienda-Power-BI/blob/main/imagenes/logo%20supertienda.png" alt="logo" width="250"/>
Tareas a realizar:

1-calcular ventas totales

2-medida calcule Total Ventas  Texas

3-columnas calcule % de ganancias

4-función IF si fue compra grande, y cuantas compras grandes hubo por región(+2500)

5-Armar un values que nos diga las ciudades únicas.

6-COUNTRROWN para saber cuantas ciudades diferentes hay

7-SUMX que nos diga precio por unidad

8-calcula venta promedio por día( tuve problemas con para transformar calendario solución reemplazando valores)

9-calcula venta promedio por cliente

10-calcula venta promedio por mes

11-mostrar todo en tabla de producto

[Fuente](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbUpSbmFGQ0VzbGZyeXlBdEpoSzEwQmx2Rnd3QXxBQ3Jtc0tud1IwclpjME5vOTlyT1hwZ0xPUVJ3UFhYT3VrekdPaU5zWlByNUVIRTlPS0g1QVBuc1A5b0hIOU1KemJpSkNNNlkySlBnNHBZZU5NMDloczVTUllYRE1teHpLR1pCY19DVHZ6a00zaUdqM2xveF9Zdw&q=https%3A%2F%2Fa2capacitacion.com%2FArchivos%2FYoutube%2FSupertienda%2BEspan%25CC%2583ol%2B-%2BA2%2BCapacitacio%25CC%2581n.csv&v=rKreQw9JGvo).

Antes de Empezar a trabajar con los datos tuve que hacer una transformación de los mismos como poner en formatos adecuados, ponerles solo dos lugares despúes de la coma, las fechas tenian este formato 41,39 y no permitía cambiarlo; primero cree una nueva columna que representara la cantidad de días transcurridos desde una fecha de referencia, como el 1 de enero de 1900, que es la fecha de inicio para el sistema de fechas utilizado en Excel y otros programas de Microsoft. DAX:Fecha = DATE(1900, 1, 1) + [Fecha de Orden], pero solo daba dos fechas del mes de febrero de 1990, luego me dí cuenta del error que era la ' , ' que no permitía hacer la transformación.

Avances del Proyecto:

<img src="https://github.com/Bearodriguez2022/Supertienda-Power-BI/blob/main/imagenes/Captura%20de%20pantalla%20(31).png" alt="logo" width="300"/>
<img src="https://github.com/Bearodriguez2022/Supertienda-Power-BI/blob/main/imagenes/Captura%20de%20pantalla%20(32).png" alt="logo" width="300"/>


El proyecto lo realicé en Power BI! <img src=https://github.com/Bearodriguez2022/RecursosHumanosPowerBI/blob/main/Imagenes/powerBI.jpg alt="powerBI" width="30"/>
, los datos estan en formato excel.

Para poder ver el dashboard primero debe tener descargado Power BI. 

Luego para ver el el proyecto precione [aquí](https://github.com/Bearodriguez2022/Supertienda-Power-BI/blob/main/Supertienda.pbix), se descargará y podra verlo.

[Contactame conmigo](www.linkedin.com/in/beatrizrodriguez-1b8482210)
