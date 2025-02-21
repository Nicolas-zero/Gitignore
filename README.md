# Gitignore

Git ve cada archivo de tu copia de trabajo de una de las siguientes maneras:

1. Con seguimiento: Un archivo que se ha preparado o confirmado previamente.

2. Sin seguimiento: Un archivo que no se ha preparado o confirmado.

3. Ignorado: Un archivo que se le ha indicado explícitamente a Git que ignore.


Los archivos ignorados suelen ser artefactos
 de compilación y archivos generados por el
 equipo que pueden derivarse de tu fuente
 de repositorios o que no deberían
 confirmarse por algún otro motivo. Estos
 son algunos ejemplos habituales:

-   Cachés de dependencias, como es el caso del contenido de `/node_modules` o `/packages`.
-   Código compilado como, por ejemplo, los archivos `.o`, `.pyc` y `.class`.
-   Directorios de salida de compilación, como es el caso de `/bin`, `/out` o `/target`.
-   Archivos generados en tiempo de ejecución como, por ejemplo, `.log`, `.lock` o `.tmp`.
-   Archivos ocultos del sistema, como es el caso de `.DS_Store` o `Thumbs.db`.
-   Archivos personales de configuración de IDE como, por ejemplo, .`idea/workspace.xml`.


A los archivos ignorados se les hace un seguimiento en un archivo especial
 llamado `.gitignore` que se incorpora en la raíz de tu repositorio.
 En Git no hay ningún comando explícito para ignorar archivos: en su lugar,
 cuando tengas nuevos archivos que quieras ignorar, deberás editar y confirmar
 manualmente el archivo `.gitignore`. Los archivos `.gitignore` contienen
 patrones que establecen coincidencias con los nombres de archivo de tu repositorio
 para determinar si deberían ignorarse o no.

