# Firmware para teclado Corne (CRKBD) – Compatible con VIA⚡
> [!IMPORTANT]
>- Asegúrate de utilizar un cable de transferencia de datos conectado a un puerto USB 3.1 (azul) para la transferencia de archivos.
>- En menos de 5 minutos, tendrás tu teclado listo para usar.
>- Este repositorio contiene el firmware listo para cargar en tu teclado Corne (CRKBD) con controladores Pro Micro, sigue la guía al pie de la letra.

> [!TIP]
> Puedes cargar el firmware antes de soldar el controlador para comprobar que este este en estado optimo para su uso, o una vez soldado en la PCB.

> [!WARNING]
>- Una vez que el proceso de carga del firmware comienza, no puede ser interrumpido.
>- Interrumpir el proceso o cargar un firmware mal compilado podría dejar el controlador en un estado inutilizable.

# 🛠️Programas necesarios
1. Descarga e instala [QMK TOOLBOX](https://qmk.fm/toolbox) <-Descarga directa para Windows y Mac.
2. Instala el programa como administrador, junto con los drivers, y descargar el firmware (archivo con extensión [.hex](https://github.com/AplyyKey/Via_firmware_crkbd/blob/main/crkbd_rev1_via.hex)).
3. Descarga e instala [VIA](https://github.com/the-via/releases/releases), un software intuitivo para configurar tu teclado <-Descarga directa para Windows y Mac.

  
# 🎛️¿Qué incluye este firmware?
- Código optimizado para mostrar caracteres de bloqueo (Mayús y Num).
- Visualización de capas de función en pantallas.
- Imagen personalizada de Corne.
- Opciones de RGB activas para una mejor experiencia visual.
- Funciones especiales habilitadas: Control de mouse, macros y multimedia.

# 🖥️Preparacion de QMK TOOLBOX
- Ejecuta **QMK TOOLBOX** como administrador.
- Instala los drivers desde la pestaña **TOOLS** o con la combinación de teclas CTRL+N.
- Selecciona el firmware descargado desde la pestaña **OPEN**.
- En la opción MCU (AVR only), selecciona **Atmega32U4** (necesario para controladores Arduino Pro Micro).
- Marca la opción de **Auto-Flash** (esto facilitará al momento de cargar el firmware)
