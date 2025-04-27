<h2>Ejercicio 10</h2>

<h4>Mostrar el texto: <p>

 “El parámetro 1 es: X” <p>
 “El parámetro 2 es: Y” <p>

- Donde X e Y serán los valores de los parámetros que se le pasan al script. <p>
- Ejecutarlo con dos parámetros cualesquiera para comprobar que funcione.</h4>

<br>

Creamos el archivo **ej_10.sh** con `nano`.
- `nano ej_10.sh`

 <img src="src/nano10.png" alt="nano" width="270" />

Ingresamos el siguiente script:
- `#!/bin/bash` <p>
  `echo "El parámetro 1 es: $1"` <p>
  `echo "El parámetro 2 es: $2"` <p>

 <img src="src/parametros.png" alt="parametros" width="270" />

  Ejecutamos el archivo **ej_10.sh** y le añadimos 2 parámetros.
- `./ej_10.sh hola adios`

 <img src="src/adios.png" alt="adios" width="270" />
