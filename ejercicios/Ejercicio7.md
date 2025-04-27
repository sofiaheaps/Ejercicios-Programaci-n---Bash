Creamos el archivo **ej_07.sh** con el editor `nano`.
- `nano ej_07.sh`

 <img src="src/nano 7.png" alt="nano" width="200" />

Ingresamos el siguiente script:
- `#!/bin/bash`<p>
  `cat "$1"`

 <img src="src/parametro.png" alt="parametro" width="130" />

El script utiliza `#!/bin/bash` para especificar el intérprete y luego usamos `cat "$1"` para mostrar el contenido del archivo que pasaremos como primer parámetro al ejecutarlo.

Ejecutamos el archivo usando el archivo "ej_01.sh" como parámetro, lo cual hace que se ejecute el contenido del ej_01.sh.
- `./ej_07.sh ej_01.sh`

 <img src="src/ejec7.png" alt="ejec" width="470" />
