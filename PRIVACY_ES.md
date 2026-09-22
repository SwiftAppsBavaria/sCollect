# Política de privacidad de sCollect

Actualizado: 2026-09-16

## En resumen

sCollect **no** recopila, almacena ni transmite datos personales. La app trabaja
exclusivamente en tu Mac. No hay cuentas, ni conexión a la nube, ni servicios de
analítica, ni publicidad.

## Qué datos procesa la app

sCollect lee y escribe los archivos de medios en las carpetas que le has entregado
expresamente, ya sea eligiéndolas en el diálogo de apertura o arrastrándolas a la
ventana. Se leen el nombre del archivo, su tamaño, su fecha y sus metadatos; se escriben
los datos que introduces en el editor.

Sin tu selección, la app no accede a ningún archivo. macOS lo impone mediante la
sandbox de apps.

## Qué deja la app en tu Mac

- **La biblioteca misma** en la carpeta que has elegido para ella: los datos del
  catálogo, las portadas y un registro de las sincronizaciones aún no ejecutadas.
- **Los ajustes y las posiciones de las ventanas** en la carpeta protegida de la app.
- **El permiso de macOS para volver a abrir tus carpetas en el siguiente inicio.** Se
  guardan rutas de carpetas, no contenidos de archivos. Solo así la app no tiene que
  preguntar de nuevo en cada inicio.
- **Un registro de diagnóstico** con los momentos y el número de operaciones. Permanece
  en tu Mac; puedes guardarlo y enviarlo si informas de un error.

Todo ello desaparece cuando borras la app y su biblioteca.

## Dos permisos que pueden plantear dudas

**Acceso a la red.** La app lo solicita porque, sin ese permiso, macOS muestra vacía la
ventana de ayuda integrada: la ayuda la presenta un componente del sistema que lo
necesita, aunque solo cargue archivos del propio programa. sCollect **no llama por sí
misma a ninguna dirección de internet**, no descarga nada y no informa de nada.

Las bibliotecas en volúmenes de red (SMB, NFS) las alcanza la app a través del sistema
de archivos de tu Mac, no mediante una conexión propia.

**Control de Apple Music.** Al exportar una lista de reproducción, sCollect abre Apple Music
con el archivo generado. macOS pide tu consentimiento para ello, y se te solicita
la primera vez. La app no controla ningún otro programa.

## Tus archivos

sCollect modifica los metadatos exactamente en los archivos que pertenecen a tu
biblioteca, y al archivarlos los mueve dentro de las carpetas que has autorizado.

**Los objetos vinculados quedan intactos**: están fuera de la biblioteca, y la app no
escribe nada ahí.

Los archivos borrados van primero a una papelera propia dentro de la biblioteca y se
pueden recuperar desde ahí. Solo se eliminan definitivamente cuando la vacías.

## Sin cesión de datos, sin analítica

No hay publicidad, ni servicios de analítica, ni informes de fallos a terceros, ni
cuentas.

## Contacto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
