# Guia de comandos de Linux
> Para ver todas las variantes de los comandos (man) nos muestra todo lo que hace con los sufijos 

<details>
  <summary>Archivos y editores</summary>
  <p>En linux todo es un fichero. Estos ficheros se organizan en una estructura de jerarquia, de tipo arbol. El nivel mas alto del sistema de fichero es / o directorio raiz. Todos los demas ficheros y directorios estan debajo.</p>
  <div>
     <h4>Grupos importantes de direcotiros de Linux:</h4>
    <div>
       <li>/bin: aplicaciones binarias importantes</li> 
       <li>/boot: Ficheros de configuracion de arranque, nucleos y otros fichero para el arranque. </li>
       <li>/dev: Ficheros de dispositivo</li>
       <li>/etc: ficheros de configuracion, scripts de arranque.</li>
       <li>/home: directorios personales</li> 
      <a href="https://help.ubuntu.com/kubuntu/desktopguide/es/directories-file-systems.html"> Ver mas sobre ficheros en GNU/Linux </a>
    </div>
  </div>
  
  <div>
    <h5>Comandos</h5>
    
  - *vim*: mas utilizado en servidores o en su otra version (vi)
    - :edit "nombre" (crea el archivo si no existe o lo edita si existe)
    - i (activa el modo escritura)
    - :w (guarda el archivo)
    - :q (salir tranqui) :q! (fuerza en la salida)
  - *nano*: es un poco mas lindo que vim tenes los comandos abajo para guiarte
  - *mcedit*: se maneja con los f1,f2,f3.. pero hayq ue instalarlo.
  - *file*: determina el tipo de archivo
  - *cat*: podemos ver las lineas del archivo
  - *more*: te permite desplazarte por el archivo
  - *less*: te permite ver linea por linea
  - *df -h /home*: con este comando podemos ver cuanto espacio nos queda en la particion
 </details>
 <details>
   
</div>
  <summary>Navegacion entre directorios y mas</summary>
  
  - *cd*: acceder a una carpeta y (*cd ..*) para salir de esa carpeta
  - *mkdir*: crea un directorio
  - *rmdir*: borra directorio
  - *ln*: crea enlaces de archivos para poder acceder en otro lugar (accesso directo)
  - *tail*: muestra las ultimas 10 lienas de una archivo o verlo en tiempo real linea por linea
  - *locate*: busca en todo el sistema un archivo
  - *find*: Busca un archivo en toda la jerarquia de directorios
  - *ls*: muestra el contenido del directorio. con ls palabra* buscamos los archivos con la palabra a buscar
  - *pwd*: muestra la ruta actual
  - *cp*: copia un archivo
  - *mv*: mover un archivo
  - *who*: Muestra usuarios activos, junto con sus terminales la hora y la IP y con "w" vemos mas lindo
 </details>
 
<details>
  <summary>Test</summary>
</details>

