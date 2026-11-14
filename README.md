# Guitar Hero: Metallica Recomp — Alpha 2

[Español](#español) · [English](#english)

## Español

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

---

## English

If you've ever wanted to play **Master of Puppets** again on your PC, this project is for you. Welcome to **Guitar Hero: Metallica Recomp Alpha 2**, an independent project bringing the Xbox 360 game to Windows with ReXGlue.

### What's new in Alpha 2?

- A Metallica-themed launcher for choosing your game folder and configuring graphics and controls.
- Keyboard profiles for guitar, bass, and five-lane drums, with a second configurable kick key. You can also set up a gamepad.
- A Debug Menu accessible from the game's main menu when compatible game files are detected.
- Direct3D 12 is recommended for playing. **Vulkan is still in development and currently unstable.**

### How it was made

This project is developed through **AI-assisted vibe coding**. My role is to set the direction, playtest the game, report the bugs I find, and decide what needs fixing. I'm sharing that process openly with the community and respecting the original authors' credits and licenses.

### What's included

| File or folder | Purpose |
| --- | --- |
| `GH Metallica Launcher.exe` | Game folder selection, graphics, and controls. |
| `GHM.exe` | Recompiled Guitar Hero: Metallica executable. |
| `rexruntime.dll` | ReXGlue runtime. |
| `rexgpu-ghmdx12.dll` and `rexgpu-ghmvk.dll` | Direct3D 12 and Vulkan renderers. |
| `shaders/` | Shader packs and pipeline caches included with the build. |

### How to play

1. Open `GH Metallica Launcher.exe`.
2. Under **Folders**, select the root folder of your Xbox 360 copy of Guitar Hero: Metallica. It contains `default.xex` and `DATA`.
3. Under **Graphics**, select Direct3D 12.
4. Under **Controls**, choose your keyboard profile and bind your guitar, bass, or five-lane drum keys. You can also configure your gamepad here.
5. Click **Save & Play** to launch the game with your settings.

You'll need your own copy of the game. The original game data is supplied separately.

### Debug Menu

The launcher applies the Debug Menu patch when it detects a folder with the expected original files. Open the Debug Menu from the game's main menu.

To open the ReXGlue settings while playing, press **Shift + F4**, or **Shift + your assigned key**.

Thanks for giving this alpha a go. If something feels off, tell me what happened and which settings you were playing with.

Join the [community Discord](https://discord.gg/tpgEvR76S) to share your tests, report bugs, and follow updates.

**brIAnelsnow** · Independent, unofficial project.
