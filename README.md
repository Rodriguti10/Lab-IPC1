# Resumen de Git

Este documento resume qué es Git, la diferencia entre el repositorio local y el remoto, y los pasos del flujo básico de trabajo.

## ¿Qué es Git y para qué sirve?

Git es un sistema de control de versiones que permite guardar el historial de cambios de un proyecto a lo largo del tiempo. Sirve para registrar cada modificación como una "versión" independiente, poder regresar a versiones anteriores si algo sale mal, y trabajar de forma ordenada incluso cuando varias personas colaboran en el mismo proyecto.

## Diferencia entre el repositorio local y el repositorio remoto

El repositorio local es la copia del proyecto que vive en la computadora del desarrollador, junto con todo su historial de commits. El repositorio remoto (en este caso, alojado en GitHub) es una copia centralizada a la que distintas personas pueden subir o descargar cambios, permitiendo que el trabajo se sincronice entre varias máquinas.

## Flujo básico de Git: status, add, commit y push

El flujo básico consta de cuatro pasos que se repiten cada vez que se modifica el proyecto. Primero, git status muestra qué archivos han cambiado. Luego, git add prepara esos cambios para ser guardados (staging). Después, git commit guarda una versión del proyecto con un mensaje descriptivo. Finalmente, git push sube esa versión al repositorio remoto en GitHub.