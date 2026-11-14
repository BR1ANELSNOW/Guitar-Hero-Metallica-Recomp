# Guitar Hero: Metallica Recomp — Alpha 2

Recompilación de Guitar Hero: Metallica de Xbox 360 para Windows x64, basada en ReXGlue. Esta Alpha incluye el launcher de Metallica, los renderizadores Direct3D 12 y Vulkan y los perfiles de teclado y joystick.

## Contenido

| Archivo o carpeta | Función |
| --- | --- |
| `GH Metallica Launcher.exe` | Selección de la carpeta del juego, gráficos y controles. |
| `GHM.exe` | Ejecutable recompilado de Metallica. |
| `rexruntime.dll` | Runtime de ReXGlue. |
| `rexgpu-ghmdx12.dll` y `rexgpu-ghmvk.dll` | Renderizadores Direct3D 12 y Vulkan. |
| `shaders/` | Paquetes de shaders y cachés de pipelines incluidos en la build. |

## Cómo jugar

1. Abrí `GH Metallica Launcher.exe`.
2. En **Carpetas**, elegí la raíz de tu copia de Guitar Hero: Metallica de Xbox 360. Es la carpeta que contiene `default.xex` y `DATA`.
3. En **Gráficos**, elegí Direct3D 12 o Vulkan según tu equipo.
4. En **Controles**, elegí el perfil de teclado y asigná las teclas de guitarra, bajo o batería de cinco carriles. También podés configurar el joystick.
5. Usá **Guardar y jugar** para iniciar Metallica con esos ajustes.

Esta build requiere tu propia copia del juego. Los datos originales se proporcionan por separado.

## Debug Menu

El launcher aplica el parche del **Debug Menu** al detectar una carpeta compatible con los archivos originales esperados. El acceso está en el menú principal del juego.

Para abrir la configuración de ReXGlue durante el juego, usá **Shift + F4** o **Shift + la tecla que hayas asignado a esa función**.

## Estado de la Alpha

- El segundo bombo de teclado se puede asignar por separado. Las dos teclas activan el mismo bombo.
- El golpe naranja de batería con la tecla `-` recibió un ajuste y queda pendiente verificarlo durante una canción.
- El perfil de teclado se configura desde el launcher. Cambiar de instrumento dentro del juego todavía no cambia automáticamente el mapa de teclas.
