# SisOp Dev Containers

Entorno de desarrollo para la materia Sistemas Operativos (UTN FRBA). Basado en Ubuntu con
herramientas C, GDB y Valgrind.

## Uso

Para agregarlo al repositorio, luego de instalar la extensión de
[Dev Containers](https://code.visualstudio.com/docs/remote/containers) en Visual Studio Code,
simplemente hay que:

1. Abrir la carpeta del proyecto
2. Hacer click en el icono de abajo a la izquierda
3. Seleccionar `Add Dev Container Configuration Files...`.
4. Elegir la opción `Add configuration to workspace`.
5. Ingresar `ghcr.io/sisoputnfrba/entorno-docker/devcontainer`
6. Hacer click en OK

Se va a crear una carpeta `.devcontainer` con un `Dockerfile` y un `devcontainer.json`. Es necesario
pushear ambos archivos al repositorio para que Codespaces lo utilice para construir el container.

## Contributors

- Agustín Ranieri [@RaniAgus](https://github.com/RaniAgus)
