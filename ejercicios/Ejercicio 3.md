<h2>Ejercicio 3</h2>

<h4>Mostrar el usuario y los grupos del usuario que ejecuta el script.
Ejecutarlo con el usuario normal y como root.</h4>

<br>

Creamos el archivo **ej_03.sh** utilizando el editor de texto `nano`.
- `nano ej_03.sh` <p>

 <img src="src/ej3.png" alt="ej3" width="260" />

Insertamos los siguientes comandos: <p>
- `echo "Usuario actual: $(whoami)"`
- `echo "Grupos del usuario: $(groups)"`

<img src="src/whoami.png" alt="whoami" width="320" />


Al ejecutar el archivo, se imprimirá por pantalla el usuario y los grupos del usuario. <p>

- `./ej_03.sh`

 <img src="src/ejecutar3.png" alt="ejecutar" width="650" />
