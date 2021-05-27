
Preguntas sobre la practica.

1. Como se capturan las interacciones en tiempo real con el teclado y como reconocer la tecla presionada.
R// Al lomento de presionar una tecla se genera un evento, este evento puede ser escuchado por el metodo addEvenListener de document y retorna informacion sobre el evento, si buscamos en el atributo keyCode podemos comparar con el de la letra que necesitamos y ejercer alguna decision.

2. Que significa la expresion "this." en prototipos javascript?
R//Hace referencia a los atributos y metodos que componen las caracteristicas de un prototipo, lo describen como cualidades y comportamientos y debe ser invocada si se pretende llamar uno de estos dentro de si mismo.

3.Que significa una funcion recursiva?
R// Es una funcion que en su ejecucion se invoca a si misma.

4.Que sucede en memoria si hacemos < var nuevoArray= arrayExistente >
R// Se va a asignar a nuevo array la misma ubicacion de memoria que a array existente, por lo que cualquier modificacion sobre array nuevo va a afectar al ya existente. eso incluye el push(ball).

