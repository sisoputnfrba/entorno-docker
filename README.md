# SisOp Dev Containers (beta)

Entorno de desarrollo para la materia Sistemas Operativos (UTN FRBA) basado en
[Development Containers](https://containers.dev/). Diseñado para cuando no sea posible utilizar
las [VMs de la cátedra](https://faq.utnso.com.ar/vms).

> [!NOTE]
> Este entorno está funcional pero aún no fue extensamente probado. Si querés ser de los
> primeros en probarlo, tu feedback es bienvenido. Ante cualquier problema, no dudes en contactarnos
> a través del [foro](https://faq.utnso.com.ar/foro).

<img width="1350" height="910" alt="image" src="https://github.com/user-attachments/assets/7f3e8b27-4c87-4e51-b131-649e833dac45" />

## Setup

Para agregarlo al repositorio, simplemente hay que:

1. Instalar la extensión de
[Dev Containers](https://code.visualstudio.com/docs/remote/containers)
2. Abrir la carpeta del proyecto
3. Hacer click en el icono de abajo a la izquierda
4. Seleccionar `Add Dev Container Configuration Files...`.
5. Elegir la opción `Add configuration to workspace`.
6. Ingresar `ghcr.io/sisoputnfrba/entorno-docker/devcontainer`
7. Hacer click en OK

Se va a crear una carpeta `.devcontainer` con un `Dockerfile` y un `devcontainer.json`. Es necesario
pushear ambos archivos al repositorio para que Codespaces lo utilice para construir el container.

## Uso

Para utilizar el devcontainer debemos crear un GitHub Codespace desde el repositorio y conectarnos
a él, ya sea desde el propio browser o desde Visual Studio Code desktop mediante la opción
`Connect to Codespace...`

## Contributors

- Agustín Ranieri [@RaniAgus](https://github.com/RaniAgus)
