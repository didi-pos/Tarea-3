<div align="center">
  <h1>Tarea 3</h1>
  <br>

  <ol>
    <li>Primero fui al <b>directorio principal</b> y con <code>pwd</code> verifiqué que estuviera ubicado correctamente en él. Luego revisé qué directorios contenía usando <code>ls</code>.</li>
    <li>Después creé un directorio llamado <b>"Practica_Linux"</b> dentro del directorio principal y comprobé su creación con <code>ls -l</code>.</li>
    <li>Ingresé al nuevo directorio y creé dos carpetas adicionales llamadas <b>"Documentos"</b> y <b>"Backup"</b>. Verifiqué que ambas se hubieran creado correctamente con <code>ls</code>.</li>
    <li>Entré en el directorio <b>"Documentos"</b> y creé un archivo llamado <b>"nota.txt"</b> usando <code>touch</code>, luego comprobé su existencia con <code>ls</code>.</li>
    <li>Con <code>nano</code> abrí el archivo <b>"nota.txt"</b>, escribí un texto dentro, lo guardé y regresé a la consola.</li>
    <li>Usé el comando <code>cp</code> para <b>copiar el archivo</b> al directorio <b>"Backup"</b> y verifiqué la copia con <code>ls</code>.</li>
    <li>En el directorio <b>"Documentos"</b> cambié el nombre del archivo de <b>"nota.txt"</b> a <b>"nota_final.txt"</b> usando <code>mv</code> y revisé el cambio con <code>ls</code>.</li>
    <li>Comprobé si el directorio <b>"Backup"</b> estaba vacío. Como no lo estaba, lo eliminé completamente (junto con su contenido) usando <code>rm -r</code>.</li>
    <li>Visualicé el contenido del archivo <b>"nota_final.txt"</b> en el directorio <b>"Documentos"</b> con el comando <code>cat</code>.</li>
    <li>Con <code>chmod</code> cambié los <b>permisos del archivo</b> para que solo el creador pudiera leer y escribir, asignándole el permiso <b>600</b>.</li>
    <li>Desde el directorio principal, busqué el archivo <b>"nota_final.txt"</b> con el comando <code>find</code>, el cual muestra la ruta completa donde se encuentra.</li>
    <li>Usé el comando <code>grep</code> para buscar una palabra específica dentro de un archivo. Este comando muestra las coincidencias encontradas, sin mostrar el nombre del archivo.</li>
    <li>Visualicé los <b>procesos activos</b> (como si fuera un administrador de tareas) utilizando el comando <code>top</code>.</li>
    <li>Probé el comando <code>sleep</code>, que pausa el terminal durante la cantidad de segundos que uno indique. Luego interrumpí su ejecución desde otro terminal usando <code>kill</code> junto con el <b>PID</b>.</li>
    <li>Actualicé el software del sistema con <code>sudo apt update</code>, ingresando la contraseña cuando se solicitó para otorgar permisos de administrador.</li>
    <li>Instalé el paquete <b>cowsay</b> con el comando <code>sudo apt install cowsay</code> para poder usarlo más adelante.</li>
    <li>Creé un <b>archivo tipo script</b> (que contiene código ejecutable) utilizando <code>nano</code>, y añadí dentro las líneas de código necesarias para su ejecución.</li>
    <li>Finalmente, le di permisos de ejecución con <code>chmod</code> y lo ejecuté desde el terminal, comprobando que el script funcionara correctamente.</li>
  </ol>
</div>
