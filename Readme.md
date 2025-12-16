# Examen 1ª Evaluación (2ª Parte) - Control de Versiones


---
## David Iglesias Pérez
## Instrucciones
- Los commits de cada apartado deben tener el mensaje *"Apartado X - descripción del cambio realizado"*
- Entrega en la tarea de Moodle tu repositorio
- Solo se corrigen los commits que estén en el repositorio remoto

### Apartado 1

- Clona este repositorio.
- Modifica este Readme, poniendo tu nombre completo, realiza un `commit` con el mensaje *"Apartado 1"* y un `push`.

Pregunta 
- ¿Qué paso es fundamental cuando clonamos un repositorio ajeno para que podamos subir nuestros propios commits? Explícalo y utiliza capturas de pantalla.
- El paso fundamental es que, después de clonar el repositorio, es necesario cambiar el remoto para que apunte a un repositorio propio, ya que en el repositorio original no tenemos permisos para subir commits.Para eso iremos a Git-Manage Remotes y cambiar la URL.
![Captura desde 2025-12-16 13-25-01.png](Captura%20desde%202025-12-16%2013-25-01.png)

### Apartado 2

- Realiza una modificación en el código en la web de tu repositorio en GitHub
- Utiliza fetch para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos para que el código modificado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.
- Para que el codigo llegue a mi rama local lo primero que hice es asegurarme de que estoy en la rama main-git checkout main, luego hice el git fetch origin para descargar los cambios del repositorio remoto que aun no estan en mi copia local y por ultimo hice un git merge origin/main para aplicar los cambios a mi rama main y que mi codigo local quede actualizado.
![Captura desde 2025-12-16 13-43-06.png](Captura%20desde%202025-12-16%2013-43-06.png)
### Apartado 3

- Realiza otro cambio desde la web de tu repositorio en GitHub.
- Utiliza pull para descargar los cambios realizados en tu repositorio.

Pregunta
- Explica los pasos dados para que el cambio realizado en GitHub, llegue a tu rama principal local. Explícalo con capturas de pantalla.

