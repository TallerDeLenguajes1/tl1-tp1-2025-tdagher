[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/kl-E8VQf)

## ¿Por qué es conveniente incluir el archivo .gitignore?
El archivo `.gitignore` es importante porque permite evitar que archivos innecesarios o sensibles sean rastreados por Git. Esto ayuda a mantener el repositorio limpio y seguro, evitando la inclusión de archivos temporales, de configuración personal o credenciales.

## ¿Cuándo se debe hacer?
Se recomienda configurar el archivo `.gitignore` al inicio del proyecto, antes de realizar el primer commit. De esta manera, se evita que archivos innecesarios sean agregados al historial del repositorio.

## ¿Cómo configurar el archivo .gitignore?
El archivo `.gitignore` contiene una lista de patrones de archivos y carpetas que Git debe ignorar. Algunos ejemplos comunes incluyen:

- `*.log` (ignora todos los archivos de logs)
- `node_modules/` (ignora la carpeta de dependencias en proyectos Node.js)
- `*.env` (ignora archivos de configuración con variables de entorno)