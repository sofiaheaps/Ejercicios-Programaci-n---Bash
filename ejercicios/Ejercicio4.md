<h2>Ejercicio 4</h2>

<h4>Mostrar el mensaje “¡Soy root!” si el usuario que lo ejecuta es root, si no
mostrar el mensaje “No soy root :(“</h4>

<br>

Creamos el archivo **ej_01.sh** utilizando el editor de texto `nano`. <p>
 
- `nano ej_04.sh` <p>

 <img src="src/nano4.png" alt="nano" width="270" />

Ingresamos el siguiente script:
- `#!/bin/bash` <p>
`if [ "$USER" == "root" ]`<p>
`then` <p>
    `echo "Soy root :)"` <p>
`else` <p>
    `echo "No soy root :("` <p>
`fi` <p>

 <img src="src/root.png" alt="root" width="320" />

El script comienza con `#!/bin/bash`, que indica que se debe ejecutar con el intérprete Bash. Luego usa `if [ "$USER" == "root" ] then` para comparar si el usuario actual es root. Si la condición es verdadera, el comando `echo "Soy root :)` muestra ese mensaje. Si no, con `else` se ejecuta "`No soy root :(`", mostrando que no somos root. Finalmente, `fi` cierra la estructura del `if`.

Al ejecutar el archivo, podemos observar que en efecto, no somos el usuario root. <p>
- `./ej_04.sh`
 <img src="src/ejecución4.png" alt="ejec" width="270" />
