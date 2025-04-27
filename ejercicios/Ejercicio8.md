<h2>Ejercicio 8</h2>

<h4>Crear una función f_hola que muestre un mensaje hola y llamarla desde el
programa principal. <p>
Utilizar un comentario en la función para documentar lo que hace.</h4>

<br>

Creamos el archivo **ej_08.sh** con el editor `nano`.
- `nano ej_08.sh`

 <img src="src/nano8.png" alt="nano" width="270" />

Creamos una función que imprima el mensaje "hola" al ejecutar el archivo.
- `#!/bin/bash` <p>
  `#Esta función te saluda` <p>
  `function hola {` <p>
      `echo "hola"` <p>
    `}` <p>
  `hola` <p>

 <img src="src/funcion.png" alt="funcion" width="220" />

  Ejecutamos el archivo:
- `./ej_08.sh`

 <img src="src/hola.png" alt="hola" width="270" />
