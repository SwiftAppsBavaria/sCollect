# Ayuda de sCollect

## Qué hace la app

sCollect gestiona colecciones de medios — música, películas, vídeos caseros,
audiolibros, podcasts, e-books — y objetos de colección que no son archivos de medios,
como monedas o sellos. Cómo se llaman las categorías lo decides tú en **Ajustes →
Etiquetas de categorías**.

Lo que introduces en el editor, la app lo escribe **de vuelta en el archivo**, y no solo
en su propio catálogo.

## Primeros pasos

1. En el primer inicio, elige una carpeta para la biblioteca. Ahí estarán después los
   datos del catálogo y, si así lo quieres, también los archivos de medios.
2. Trae archivos o carpetas con **Archivo → Importar archivos** (⌘O) o **Archivo →
   Importar carpeta** (⇧⌘O), o arrástralos a la ventana.
3. Al importar decides, en cada pasada, si los archivos se **copian a la biblioteca** o
   solo se **vinculan**.

## ¿Gestionado o vinculado?

| | |
|---|---|
| **Gestionado** | El archivo está en la biblioteca. sCollect lo archiva, lo nombra según tu esquema y escribe las etiquetas. |
| **Vinculado** | El archivo se queda donde está. sCollect recuerda el lugar y **no toca el archivo**. |

La columna «Vinculado» de la lista muestra cuál es el caso.

## Preguntas frecuentes

**Una entrada tiene un triángulo de advertencia naranja.**
Su archivo no se encontró en la última pasada de **Archivo → Biblioteca → Marcar los
ítems faltantes**. La entrada no se puede editar entonces: no hay nada donde escribir. En el
menú contextual la app ofrece **Buscar archivo…**; el archivo encontrado se devuelve a
la biblioteca.

**En el menú contextual aparece «Unidad no conectada», atenuado.**
Entonces no falta el archivo, sino el disco. sCollect distingue expresamente los dos
casos: lo que no está conectado tampoco se puede comprobar — y por eso no se marca como
faltante. Conecta el disco y vuelve a lanzar la pasada.

**Un tipo de medio está gris y no se puede cambiar.**
Su carpeta no está accesible en este momento. sCollect bloquea esos tipos en vez de
guardar los archivos en otro sitio sin decir nada. En cuanto el disco vuelve, el bloqueo
desaparece.

**El editor muestra «Un campo difiere del archivo».**
En un campo el archivo lleva algo distinto de la biblioteca, casi siempre porque otro
programa lo ha editado entretanto. La banda sobre los campos indica cuáles están
afectados, y tú decides campo por campo si se toma el valor del archivo.

**No encuentro un campo que necesito.**
Para los objetos de colección hay tres campos de nombre libre. Cómo se llaman se ajusta
por categoría en **Ajustes → Etiquetas de campos**.

**¿Puedo traerme mi colección de iTunes o Música?**
Sí. sCollect lee el XML de iTunes, con valoraciones y listas de reproducción. Las pistas
se asignan por sus rutas de archivo; las valoraciones existentes no se sobrescriben.

**¿Cómo vuelvo a sacar mi colección?**
Con el **sCollect-XML**: es sin pérdidas y sirve al mismo tiempo como copia de
seguridad. Además está la exportación como XML de iTunes y como lista de reproducción
para Apple Music.

**¿Qué hace la sincronización con las copias?**
Una biblioteca puede registrar otras bibliotecas como copias. Los cambios en el fondo
principal se trasladan ahí, archivos y etiquetas incluidos. Si una copia está sin
conexión, el cambio queda pendiente y se aplica más tarde.

⚠️ **Esto no es una copia de seguridad.** Un archivo borrado se borra también en las
copias: para eso sirve una sincronización. Por si algo sale mal, necesitas además una
copia de seguridad de verdad.

**¿Pierde calidad mi archivo al escribir las etiquetas?**
No. Los datos de audio e imagen se conservan sin cambios; no se recodifica nada. Donde
es posible, sCollect cambia solo los pocos bytes de la etiqueta en vez de reescribir el
archivo.

**¿Puedo deshacer un cambio?**
⌘Z recupera las entradas borradas. Los cambios en los metadatos, no: haz por eso una
copia de seguridad antes de un gran proceso por lotes.

## ¿Algo ha salido mal?

sCollect escribe un registro en la carpeta de tu biblioteca: anota qué ha hecho la app y
cuándo. Envíalo junto con la descripción del error.

## Contacto

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
