Creamos el archivo **ej_05.sh** con el editor nano:
- `nano ej_05.sh`

 <img src="src/nano5.png" alt="nano" width="200" />
 
Dentro del archivo, creamos un bucle que repite el mensaje "Esto es un mensaje" 8 veces.

- `for ((I=1; I<9; I++))` <p>
`do` <p>
  `echo "8 veces" $I` <p>
`done`

 <img src="src/repeticiones.png" alt="repeticiones" width="270" />

El script comienza con `#!/bin/bash` para indicar el uso de Bash. Luego utiliza el bucle `for ((I=1; I<9; I++))` que repite 8 veces el mensaje proporcionado, incrementando la variable I de 1 a 8. Dentro del bucle, `echo "Esto es un mensaje" $I` muestra el mensaje 8 veces seguido del número de iteración en cada vuelta, y el bucle se cierra con `done`.

Al ejecutar el archivo, se ha imprimido el mensaje un total de 8 veces.
- `./ej_05.sh`

 <img src="src/ejecu5.png" alt="ejecucion" width="200" />
