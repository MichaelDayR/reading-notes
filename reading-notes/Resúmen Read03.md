# Read 03
## Respondiendo Preguntas / Traduciendo el texto
### ¿Qué es el control de versiones?
Es un sistema que te permite revisitar varias versiones de uno o más archivos al registras los cambios realizados. A través de la version de control, uno puede revertir los cambios realizados,  encontrar las modificaciones realizadas y modificarlas individualmente, comparar cambios. Al utilizar una *VersionControlSystem (VCS)*, los errores pueden ser subsanados con mayor facilidad.
Version de control LOCAL
- Permite que los programadores puedan crear una base de datos en sus propios discos duros y guardar los cambios realizados.
- Hay un sistema centralizado de versiones el cual permite acceder a ver y o realizar cambios a más de una persona. De la misma manera hay un registro de los cambios realizados para que sea más sencillo entender cómo se encuentra configurado el proyecto en la actualidad.
- La version de distribucion del control, permite que no solo haya una copia de segurirdad del proyecto de programación, sino que cada persona involucrada en la codificación pueda tener una copia. De esta manera si por alguna complicación el núcleo se malogra o se borra, las personas involucradas en el proyecto tienen un 'backup' en su disco local.

¿Qué es la “cloning” en Git?

Cloning es una herramienta que te permite *clonar, duplicar, crear una copia* del archivo deseado en el disco local. Lo cual trae principalmente 2 beneficios:
- Seguridad por si algún siniestro sucede con el archivo o conjunto de archivos en el núcleo.
- Permitir que podamos trabajar en un código o conjunto de códigos de manera *offline*

¿Cuál es el comando para rastrear y preparar archivos?
- git status te permite ver los archivos  y determinar su **estado**
- git add filename te permite trackear un archivo. Puedes usar **All Files** y juntas todos los archivos en un repositorio, puedes usar una * para hacerlo.

¿Cuál es el comando para tomar una instantánea de los archivos modificados?
- el comando es: git commit -m "aqui puedes poner mensajes para los humanos que esten involucrados en el proyecto"
- commit a >realiza un commit a todos los cambios realizados en el repositorio.
¿Cuál es el comando para enviar los archivos modificados a Github?
- el comando es: git push

*Esto hace que despues usea el "commit" puedas lanzar tu royectoa la **red** y dependiendo de la plataforma que uses (en nuestro caso GitHub) podras ver los cambios.*