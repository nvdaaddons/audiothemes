# Audio Themes #

*   Autores: Musharraf Omer y otros
*   descargar [versión estable][1]
*   descargar [versión de desarrollo][2]

Este complemento crea una pantalla de audio virtual que reproduce sonidos
cuando se enfoca o se navegan objetos (tales como botones, enlaces etc...)
el audio se reproducirá en una localización que corresponda a la
localización de los objetos en la pantalla visual.

El complemento también te capacita para activar, instalar, eliminar, editar,
crear, y distribuir paquetes de temas de audio.

## Utilización

Este complemento te capacita para llevar a cabo tres tareas distintas,
incluyendo administrar tus temas de audio instalados, editar el tema de
audio actualmente activo, y crear un tema de audio nuevo.

Puedes acceder a estas funciones desde el menú del complemento que se
encuentra en el menú principal de NVDA.

### Administrando tus Temas de Audio

- El diálogo 'Administrar Temas de Audio' te capacita para activar o
  desactivar temas de audio, además de instalar y eliminar temas de audio.
- En este diálogo hay algunas opciones adicionales incluyendo:
 - Reproducir sonidos en modo 3D: cuando desmarques esta casilla el complemento reproducirá los sonidos en modo mono (siempre en el centro de la pantalla audio) independientemente de la localización del objeto.
 - Verbalizar rol tal como botón, cuadro de edición, enlace etc.: Cuando desmarques esta casilla NVDA arrancará anunciando el rol cuando se enfoquen objetos en lugar de ignorarlos (lo cual es el comportamiento predeterminado cuando se instala este complemento).
 - Utilizar Volumen del Sintetizador : marcando esta casilla configurará el reproductor de sonido de este complemento para utilizar el sonido de la voz activa, con lo que toda la salida audible es la misma que el volumen de la voz cada vez que cambies el volumen.
 - Deslizador del Volumen del Audio del Tema: alternativamente puedes configurar el volumen para el complemento utilizando este deslizador. Poniéndolo a 0 silenciarás todos los sonidos, y 100 es el volumen máximo.

### Editando el Tema de Audio Activo:

- Cuando hagas clic en la opción 'Editar el tema de audio activo', se abrirá
  un diálogo con una lista conteniendo todos los sonidos dentro del tema
  actualmente activo. Desde este diálogo puedes:
- Cambiar Seleccionado: seleccionando un sonido desde la lista y haciendo
  clic en este botón, abrirás un diálogo estándar abrir fichero, selecciona
  un fichero ogg o wave de tu sistema de ficheros para reemplazar el sonido
  seleccionado, y haciendo clic en Aceptar completas el proceso.
- Eliminar Seleccionado: esto eliminará el sonido seleccionado del tema, ha
  clic en 'sí' para confirmar el proceso de borrado, y el sonido
  seleccionado se eliminará.
- Añadir Sonido Nuevo: al hacer clic en este botón se mostrará un diálogo nuevo. Desde el primer cuadro combinado en el nuedo diálogo abierto selecciona el tipo de objeto al que quieres asignar el sonido, por ejemplo (botón, enlace, pestaña, menú y así), entonces haz clic en el botón 'Buscar un fichero de Audio' para seleccionar el sonido que quieras asignar para el tipo de objeto seleccionado anteriormente. Opcionalmente puedes hacer clic en el botón previsualizar para previsualizar el sonido, y finalmente haciendo clic en el botón Aceptar aplicarás los cambios y asignarás el sonido seleccionado al objeto seleccionado. 
- Cerrar: saldrá del diálogo sin realizar ninguna acción.

### Creando un Nuevo Tema de Audio

- Si tienes una buena capacidad de producción de sonido puedes aplicarla
aquí y crear un tema de audio de tu propiedad, en lugar de editar una
existente. Para hacer esto puedes seguir estos pasos.  - Recolecta tus
ficheros de audio en un lugar, deben estar en formato ogg o wave, y
renómbralos a algo que tenga sentido para ti. Por ejemplo cuando yo estaba
creando el teman de audio predeterminado para este complemento, agrupé los
sonidos de acuerdo a patrones de interacción, por ejemplo, el cuadro
combinado, el botón desplegable, y el botón de separación pueden tener el
mismo sonido, mientras que la Casilla de verificación, el botón conmutable,
y el elemento verificable de menú pueden tener el mismo sonido.  - Desde el
menú del complemento haz clic en 'Crear un tema de audio nuevo' - se abrirá
un nuevo diálogo preguntándote por alguna información acerca de tu tema de
audio nuevo, incluyendo: *	El nombre del tema: el nombre de tu tema el cual
se mostrará en el administrador de temas de audio. Esto debe ser un nombre
de carpeta válido de windows.  *	Tu Nombre: introduce tu nombre real o un
seudónimo.  *	Descripción de Tema: una descripción breve acerca de tu tema
de audio.  - Haz Clik en Aceptar para moverte al siguiente paso.  - En el
siguiente paso se mostrará un diálogo similar 'Editor de Temas Audio', y el
proceso es el mismo que el proceso de edición, así que refiérete a la
sección 'Editando el Tema de Audio Activo'.

## Copyright:

Copyright (c) 2014-2016 Musharraf Omer y Otros

A pesar de que este complemento se comenzó como un proyecto independiente,
evolucionó desde ser una versión mejorada del complemento 'Unspoken' de
Austin Hicks y Bryan Smart. La mayoría del desarrollo de este complemento
estuvo creando las herramientas para administrar, editar y crear los
paquetes de temas de audio. Así que les agradezco mucho por la creación de
tal maravilloso complemento, y hacerlo disponible para que nosotros
construyamos sobre su trabajo.

## Una nota sobre Ficheros de Terceros:

El paquete de temas de audio **Predeterminado** en este complemento utiliza
sonidos de varias fuentes, esta es una mención para ellos: - Unspoken 3D
Audio: Un complemento para NVDA - TWBlue: un cliente libre y de código
abierto de twitter - Mushy TalkBack: una alternativa de talkback con mejores
sonidos.

## Licencia
Licenciado bajo la GNU General Public License. Consulta el fichero
**copying** para más detalles.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=ath

[2]: https://addons.nvda-project.org/files/get.php?file=ath-dev
