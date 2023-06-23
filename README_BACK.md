Pasos para desplegar el proyecto =>

1-Abrir el eclipse

2-Dentro de Eclipse... File > Import > Existing Maven Projetcts y seleccionamos el proyecto

3-No me da tiempo a montarlo todo en un servidor y no quiero demorarme mucho más en mandar la prueba, por lo que he hecho lo que he podido.

4-Para lanzarla simplemente lanzar el main de la clase "Principal".
(Una vez ejecutado por primera vez, comentar los métodos creacionTablas() e insertarTablas() para evitar errores).
(Nunca he utilizado H2, no se si al importar el proyecto las tablas se mantienen creadas o no, si os da error al lanzarlo, comentad los metodos que os he dicho).

La aplicación funciona todo en local, con la bbdd H2, hay varias funciones:
	creacionTablas() => Crea las dos tablas con sus restricciones
	insertarDatos() => Obtiene los datos de los CSV aportados, los controla y los inserta en las tablas
	obtenerProvinciaPorCodigo(int codigoProvincia) => Obtiene los datos necesarios dado el codigo de provincia por parámetro.
	obtenerProvinciaPorComunidadAutonoma(String codigoCA) => Obtiene los datos necesarios dado el codigo de comunidad autonoma por parámetro.