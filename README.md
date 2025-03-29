# flujo-git
Flujo de Trabajo con GitFlow

Este repositorio sigue un flujo de trabajo basado en GitFlow, que permite organizar los cambios y mejoras en el proyecto de forma estructurada. Aquí te cuento lo que hice paso a paso:

1. Creé el repositorio en GitHub

Primero, entré a GitHub y generé un nuevo repositorio para este ejercicio. Luego, copié la URL para poder trabajarlo en mi computadora.

2. Cloné el repositorio en mi PC

Usando Git Bash, descargué el repositorio en mi computadora para poder trabajar con él.

3. Creé las ramas necesarias

Para organizar mejor los cambios, seguí la estructura de GitFlow y creé varias ramas:
	•	develop → Para el desarrollo principal.
	•	release → Para preparar la versión final antes de subirla a producción.
	•	feature-1 y feature-2 → Para trabajar en cambios específicos sin afectar el código principal.

4. Trabajé en las ramas de feature

Cada cambio lo hice en una rama aparte para no afectar las demás. Por ejemplo, en feature-1 hice algunos cambios, los guardé y los envié al repositorio. Luego, hice lo mismo con feature-2.

5. Uní los cambios en la rama develop

Cuando terminé de trabajar en las ramas de feature, los junté en develop, que es donde se integran todas las mejoras antes de preparar una versión final.

6. Preparé la versión final en release

Después de tener todo listo en develop, creé la rama release para hacer los últimos ajustes antes de lanzarlo.

7. Subí todo a producción (main)

Cuando todo estaba probado y listo, fusioné release con main, que es la versión final del proyecto.

8. Documenté el proceso

Para dejar un registro de lo que hice, creé este archivo README.md con una explicación clara del proceso
