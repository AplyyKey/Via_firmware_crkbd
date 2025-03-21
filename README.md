# Firmware para teclado Corne (CRKBD) – Compatible con VIA⚡

> [!IMPORTANT]
> Asegúrate de utilizar un cable de transferencia de datos conectado a un puerto USB 3.1 (azul) para la transferencia de archivos.
> Este repositorio contiene el firmware listo para cargar en tu teclado Corne (CRKBD) con controladores Pro Micro.
> Sigue la guía al pie de la letra.

> [!TIP]
> Si aún no has soldado el controlador, carga el firmware para verificar su funcionamiento, o hazlo una vez esté soldado en la PCB.

> [!WARNING]
> Una vez que comience el proceso de carga del firmware, no debe interrumpirse. Interrumpir el proceso o cargar un firmware mal compilado puede dejar el controlador en un estado inutilizable.

# 🛠️Programas necesarios
- Descarga e instala [QMK TOOLBOX](https://qmk.fm/toolbox) (para **Windows** y **Mac**).
- Instala el programa como administrador, junto con los drivers, y descargar el firmware (archivo con extensión [.hex](https://github.com/AplyyKey/Via_firmware_crkbd/blob/main/crkbd_rev1_via.hex)).
- Descarga e instala [VIA](https://github.com/the-via/releases/releases), un software intuitivo para configurar tu teclado (para **Windows** y **Mac**).
  
# 🎛️¿Qué incluye este firmware?
- Código optimizado para mostrar caracteres de bloqueo (Mayús y Num).
- Visualización de capas de función en pantallas.
- Imagen personalizada de Corne.
- Opciones de RGB activas para una mejor experiencia visual.
- Funciones especiales habilitadas: Control de mouse, macros y multimedia

<img src="https://github.com/user-attachments/assets/5aab29d2-7863-4741-b80b-7d4a4e45bf25" width="40%" />


# 🖥️Preparacion de QMK TOOLBOX
- Ejecuta **QMK TOOLBOX** como administrador.
- Instala los drivers desde la pestaña **TOOLS** o con la combinación de teclas CTRL+N.
- Selecciona el firmware (archivo con extensión [.hex](https://github.com/AplyyKey/Via_firmware_crkbd/blob/main/crkbd_rev1_via.hex)) descargado desde la pestaña **OPEN**.
- En la opción MCU (AVR only), selecciona **Atmega32U4** (necesario para controladores Arduino Pro Micro).
- Marca la opción de **Auto-Flash** (esto facilitará al momento de cargar el firmware)

# ▶️Explicación 
- Cargaremos el firmware en ambas mitades de manera individual. Usa un cable de transferencia de datos en un puerto USB 3.1 (azul) y asegúrate de que el cable TRRS no esté conectado.
- Luego, presiona una vez el pulsador ubicado en la PCB para poner cada controlador en modo de programación.
- El programa cargará el firmware automáticamente. Asegúrate de seleccionar **Auto-Flash** para que el proceso sea automático.
- Podrás verificar que la carga se ha completado con éxito cuando **QMK TOOLBOX** muestre el mensaje "**Flash complete**".

<img src="https://github.com/user-attachments/assets/4223266b-0cf8-4fae-b939-47770f143a53" width="35%" /> <img src="https://github.com/user-attachments/assets/593b3e70-8457-465d-b413-465ab40fcd0a" width="41.2%" />

# ▶️Controlador 
- Para cargar el firmware con el controlador libre, realiza un puente entre los puntos GND y RESET (puedes hacerlo con un alambre, clip o pinzas de electrónica).
  
<img src="https://github.com/user-attachments/assets/8e5d6935-1b09-474b-afc0-46683d21c623" width="25%" />
