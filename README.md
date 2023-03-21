<div id="header" align="center">
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Gestion_de_ventas.PNG"/>
  <h1 align="center">Que bueno verte!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
  </h1>
</div>

## Qlik_Sense_Project
En este repositorio comparto un proyecto en el cual trabajé sobre un caso empresarial de ventas. Esta herramienta es una verdadera joya que nos permite monitorear y analizar el rendimiento de ventas en tiempo real. 

Con este dashboard, podremos visualizar nuestras ventas por mes o año, así como también su comparación. También podremos monitorear las ventas por región, producto, cliente y tienda, lo que nos permitirá identificar oportunidades de crecimiento y optimización, asi como tambien tomar decisiones informadas en función de los datos.

¿No les parece increíble? Esta herramienta revoluciona la manera en que tomamos decisiones y alcanzamos el éxito.

### 1. Back end

Se trabajó con una metodología de aplicación de análisis de datos por capas:

1-Procesos de extracción (QVDs y QVSs de extracción)

2-Procesos de transformación (QVDs y QVSs de transformación)

Se persiguió un modelo tipo estrella, donde la base de datos se encuentra desnormalizada.
Es decir que se obtiene una gran tabla de hechos o transaccional conectada con tablas maestras que contienen dimensiones. Estas asociaciones entre tablas se conectan a partir de campos clave.

<div id="header" align="center">
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Modelo_estrella.PNG"   width="800px"/>
  </div>

### 2. Análisis y Visualización de datos

A partir de los QVDs obtenidos (transformados y no transformados) se crearon hojas de análisis interactivas de Clientes, Productos y Tiendas.
Luego se resumió la información relevante en un Dashboard.

<div id="header" align="center">
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Clientes_1.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Clientes_2.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Productos_1.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Productos_2.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Tiendas_1.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Tiendas_2.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Dashboard_1.PNG"/>
  
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Dashboard_2.PNG"/>
  
  </div>

### Ejémplo selección especial año 2008 
Una gran funcionalidad de esta aplicación es que es interactiva! Permite al usuario explorar los datos de manera más profunda y personalizada. En lugar de simplemente presentar información estática, permiten seleccionar diferentes variables y parámetros, cambiar la escala de tiempo y ver diferentes perspectivas de los datos. Además, hacen que navegar sea más emocionante. Esto puede resultar en una mejor comprensión de los datos y en la identificación de patrones y tendencias que no serían evidentes en una presentación estática.

<div id="header" align="center">
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Seleccion_2008.png"/>
  <img src="https://github.com/Dlavec/Qlik_Sense_Project/blob/main/Images/Seleccion_2008_2.png"/>
  </div>
