# OrganizArt
Un conjunto de atajos, scripts y procesos para macOS que automatizan la creación, organización y mantenimiento de árboles de carpetas. 

Lee mi [artículo](https://castro.eus/expriments/organizart) para una descripción completa.

## Instalación 

[Apple Shortcuts](https://support.apple.com/es-es/guide/shortcuts/welcome/ios) y [Automator](https://support.apple.com/es-es/guide/automator/welcome/mac) vienen instalados por defecto dentro de macOS

1. Descarga el atajo [OrganizArt](https://www.icloud.com/shortcuts/e6f3f9f2ccaf4e80a7354e7742ebcc30)
2. Asegúrate de que el atajo tiene las opciones `Mostrar en compatir` y `Usar como Acción rápida` tanto en Finder como en el Menú de servicios. Estas opciones se activan dentro del editor de Atajos en el icono de información arriba a la derecha. 
3. Descarga el Workflow de Automator y ábrelo como Folder Action. 
4. Haz click derecho en la carpeta de destino, elige la opción `Acciones rápidas` y clicka en OrganizArt.
5. Haz click en la carpeta que has creado y esta vez clicka en `Configuración de Acciones de Carpeta`
6. Click-a en ejecutar servicio y selecciona en el siguiente menú OrganizArt.Workflow, al final de la lista.

Con esto, tienes todo listo y las carpetas se adaptaran automáticamente.

## Modificación del script (Avanzado)

Si quieres modificar el script para que se adapte a tus necesidades mejor, solo tienes que saber un poco de Bash y la estructura de atajos de Apple.

### Atajos 

Si quieres crear o cambiar carpetas solo debes tener en cuenta la variable a la que está señalando. Por ejemplo, `_Caché` está dentro de la carpeta de Vídeos porque la variable de creación de carpetas apunta a `Vídeos`, no a la de `Entrada proporcionada`. Si prefieres un vídeo explicativo [aquí](https://www.youtube.com/watch?v=L12y1jUlKfo&t=54s) tienes uno. 

### Automator 

Para el workflow de Automator, puedes usar ChatGPT si no sabes programar. Pero solo has de fijarte en qué tipos de archivos quieres dentro de cada variable. Si quieres separarlos en más directorios, cambia ese tipo de archivo a otro directorio.







