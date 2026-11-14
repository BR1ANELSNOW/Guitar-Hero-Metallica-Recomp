# Guitar Hero: Metallica Recomp — Alpha 2

Si alguna vez quisiste volver a tocar **Master of Puppets** en tu PC, este proyecto es para vos. Esta es la **Alpha 2 de Guitar Hero: Metallica Recomp**, un proyecto independiente para llevar el juego de Xbox 360 a Windows con ReXGlue.

## ¿Qué trae la Alpha 2?

- Un launcher con la estética de Metallica para elegir la carpeta del juego y configurar gráficos y controles.
- Perfiles de teclado para guitarra, bajo y batería de cinco carriles, con un segundo bombo configurable. También podés configurar el joystick.
- El Debug Menu desde el menú principal del juego, con archivos compatibles.
- Direct3D 12 es la opción recomendada para jugar. **Vulkan sigue en desarrollo y por ahora es inestable.**

## Cómo se hizo

Este proyecto se desarrolla con **vibe coding asistido por IA**. Mi parte es marcar el rumbo, probar el juego de verdad, reportar los fallos que encuentro y definir qué hay que corregir. Lo comparto con la comunidad con ese proceso a la vista y respetando los créditos y licencias de los autores originales.

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
3. En **Gráficos**, elegí Direct3D 12 para jugar. Vulkan sigue en desarrollo y por el momento es inestable.
4. En **Controles**, elegí el perfil de teclado y asigná las teclas de guitarra, bajo o batería de cinco carriles. También podés configurar el joystick.
5. Usá **Guardar y jugar** para iniciar Metallica con esos ajustes.

Esta build requiere tu propia copia del juego. Los datos originales se proporcionan por separado.

## Debug Menu

El launcher aplica el parche del **Debug Menu** al detectar una carpeta compatible con los archivos originales esperados. El acceso está en el menú principal del juego.

Para abrir la configuración de ReXGlue durante el juego, usá **Shift + F4** o **Shift + la tecla que tengas asignada**

Gracias por darle una oportunidad a esta Alpha. Si la probás y encontrás algo raro, contame qué pasó y con qué configuración estabas jugando.

Sumate al [Discord de la comunidad](https://discord.gg/tpgEvR76S) para compartir tus pruebas, reportar errores y seguir las novedades.

**brIAnelsnow** · Proyecto independiente y no oficial.
