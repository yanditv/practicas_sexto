---
sidebar_position: 1
---


**CREACION DE CUBOS DE DATO**

1.Primero descargamos la extensión “MICROSOFT ANALYSIS SERVICES PROJECTS”, y la instalamos.

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.002.png)

2.Ahora damos click en crear un nuevo proyecto y buscamos “Proyecto multidimensional”, lo seleccionamos y damos click en “NEXT”:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.003.png)

3.Ingresamos un nombre para el proyecto y damos click en “Create”:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.004.png)

4 Ahora en el nuevo proyecto damos click derecho sobre “Data Source” y en “New Data Source”:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.005.png)

5.Ahora, tenemos que agregar una nueva conexión, para eso debemos agregar el nombre del servidor local de sql server.

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.006.png)

6.Una vez definido el nombre del servidor debemos agregar la autenticación, que en este caso usaremos “SQL SERVER AUTHENTICATION”, ingresamos nuestro usuario y password.

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.007.png)

7.Ahora, también elegimos la base de datos que vamos a usar y guardamos la conexión:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.008.png)

8.Ahora necesitamos agregar las vistas de datos, dando click sobre “Data Source Views” y en “New Data Source”:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.009.png)

9.Elegimos nuestra base de datos que vamos a usar y damos click en “Next”:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.010.png)

10.Una vez seleccionada la base de datos elegimos las tablas que queremos usar:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.011.png)

11.Le asignamos un nombre a nuestras vista y damos click en “Finish”

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.012.png)

12.Ahora agregamos un nuevo cubos:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.013.png)

13.Elegimos la opción de “Usar tablas existentes”:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.014.png)

14.Elegimos las tablas que queremos usar:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.015.png)

15.Elegimos las medidas que usará el cubo para procesar los datos.

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.016.png)

16.Casi para terminar seleccionamos las dimensiones que tendrá el cubo:

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.017.png)

17.Y listo tendremos nuestro cubo de datos

![Locale Dropdown](./img/Aspose.Words.30f61a41-6501-42c8-8a6a-598c0392c556.018.png)
