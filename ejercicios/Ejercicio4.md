Creamos el archivo **ej_01.sh** utilizando el editor de texto `nano`.
- `nano ej_04.sh` <p>

Ingresamos el siguiente script:
- `#!/bin/bash` <p>
`if [ "$USER" == "root" ]`<p>
`then` <p>
    `echo "Soy root :)"` <p>
`else` <p>
    `echo "No soy root :(" <p>
`fi` <p>

El script comienza con `#!/bin/bash`, que indica que se debe ejecutar con el intérprete Bash. Luego usa `if [ "$USER" == "root" ] then` para comparar si el usuario actual es root. Si la condición es verdadera, el comando `echo "Soy root :)` muestra ese mensaje. Si no, con `else` se ejecuta "`No soy root :(`", mostrando que no somos root. Finalmente, `fi` cierra la estructura del `if`.
