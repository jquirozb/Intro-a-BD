#Bases de Datos en la nube aplicado a tu Proyecto

###Objetivo
Que el alumno aplique conocimientos de esta sesión en su proyecto personal. 

###Requisitos
1. Repositorio actualizado. 
2. Usar la carpeta de trabajo Sesion08/Postwork
3. MongoDB Atlas configurado
4. Compass instalado, corriendo y conectado al Cluster MongoDB
5. Conjuntos de datos del proyecto que desees analizar
6. Cuenta en MongoDB Atlas

###Desarrollo
1. Realizar una conexión desde Compass a la base de datos creada en MongoDB Atlas. 
Acceso: mongodb+srv://introabd:introabd1234@cluster0-2g3p6.mongodb.net/test?authSource=admin&replicaSet=Cluster0-shard-0&readPreference=primary&appname=MongoDB%20Compass&ssl=true

2. Analizar la estructura de los datos para conocer el contexto y poder formular preguntas. 
Campos: Currency (nombre de criptomoneda), Date (fecha de los datos), open (precio de apertura al inicio del día), high (precio máxico en ese día), low (precio mínimo en ese día),
close (precio de cierre al final del día), volume (valor monetario de las transacciones realizadas ese día), market cap (capitalización de mercado, e. i: precio de la moneda x oferta circulante). 

*Los precios están en USD. 

3. Formular preguntas sobre el conjunto de datos. 
- ¿Máximo precio que han alcanzado Bitcoin, Litecoin y Ethereum desde el 2013?
- ¿Mínimo precio que han alcanzado Bitcoin, Litecoin y Ethereum desde el 2013?
- ¿Qué moneda tiene la mayor capitalización de mercado?
- ¿Qué moneda es más volatil?
- ¿Hay algún día de la semana donde convenga más comprar/vender?
- ¿Las criptomonedas están correlacionadas con el movimiento de la economía?

4. Por cada pregunta, realizar las consultas o ajustes necesarios a los datos para poder responderlas. 
Las primeras 3 preguntas están contestadas en los otros documentos incluidos en este repositorio. 
Las demás se contestarán más adelante en el curso (en los módulos de R y Python).




