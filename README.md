Este es un script simple en BATCH para monitorizar una carpeta e imprimir los PDFs que tenga de forma automatica y luego borrarlos. La idea surge de la necesidad de imprimir desde el movil en la calle archivos PDF de partes de trabajo que voy recibiendo.

Podras guardar desde el movil o cualquier otro dispositivo un PDF a una carpeta de Dropbox, Drive, OneDrive, etc... que estaremos monitorizando con este script a traves del PROGRAMADOR DE TAREAS de Windows lanzandolo cada 30 minutos o el tiempo que queramos. 
De este modo podremos imprimir de forma remota en nuestra impresora por vieja que sea.

Para ello el script crea un listado TXT de los archivos de la carpeta (SOLO DEBE CONTENER PDFs que posteriormente borrará) y los ira imprimiendo uno por uno con SumatraPDF (esta dentro del RAR)

Si no queremos modificar mucho el codigo la carpeta de este script (pdf) debe copiarse a la raiz de la unidad C: con el mismo nombre o modificar sus rutas para que funcione correctamente.

Es importante que las rutas no contengan espacios, de lo contrario no funcionara o tendremos que editar el codigo para ello.

Los argumentos de SumatraPDF estan aqui: https://www.sumatrapdfreader.org/docs/Command-line-arguments

Este codigo es libre y puedes usarlo como quieras.
