en este documento podras encontrar la creacion de una data mart donde encontraras toda la documentacion necesaria

extraccion

primeramente se realiza la extraccion de las tablas antes dadas en la base de datos jardineria, en donde cada tabla tuvo la extraccion de las celdas necesarias para que se utilizaran en la base de datos staging donde solamente llegara la informacion necesaria y filtrada para realizar el siguiente paso

transformacion

en esta fase se realiza la transformacion de los datos que se encuentran en las tablas de la base de datos de staging, logrando asi que la calidad de los datos sea mas alta y que no aparezcan datos null o en su defecto datos innecesarios, asi con esto se crean las tablas de dimension que ahi es donde se almacenaran los datos ya filtrados y por ende tampoco se recibiran datos duplicados
despues procedemos a crear la tabla de hechos que en nuestro caso es Fac_Ventas, que es la responsable de tener en ella los datos cruzados de las dimensiones unificando la informacion importante y dando como resultado una tabla con las caracteristicas necesarias para realizar su proposito dar una factura con un total veridico 

carga

en este paso ya cargamos los datos a la data mart final asegurandonos de que cada tabla, este lista sin datos duplicados y con las nuevas entradas, dando como resultado una informacion solida y de mejor calidad
