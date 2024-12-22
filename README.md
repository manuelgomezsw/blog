# Agregar contenido
Hay dos formas, manual y vía comando:
1. Manual: crear el archivo con extensión `.md` en `/content/posts/`.
2. Comando: ejecutar el comando `hugo new content content/posts/nombre-archivo.md`.

# Ejecutar en modo local
Para iniciar el blog en modo local no es más que ejecutar el comando `hugo server` y listo.

# Desplegar versión
1. Autenticarse en firebase `firebase login`.
2. Compilar y desplegar la nueva versión `hugo && firebase deploy`.

# Referencias
### Comando Title-Formatter
Para transformar el título, ejecutar la funcionalidad: `go run main.go -title="Lorem impsum dolor"` ubicado en la ruta `/Repos/Manu/transform-title`.

### Prompt ChatGPT
Cuáles serían las 4 palabras claves que mejor representan esta entrada "". Listalas separadas por coma.