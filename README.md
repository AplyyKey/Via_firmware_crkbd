# Firmware para teclado Corne (CRKBD) – Compatible con VIA⚡
Este repositorio contiene el firmware listo para cargar en tu teclado Corne (CRKBD) con controladores Pro Micro.

# 🛠️¿Cómo instalarlo?
1. Descarga e instala [QMK TOOLBOX](https://qmk.fm/toolbox) <- Lo puedes descargar directamente desde la pagina para sistemas operativos Windows y Mac 
2. Instala el programa como administrador, junto con los drivers, y precarga el firmware previamente descargado (archivo con extensión [.hex](https://github.com/AplyyKey/Via_firmware_crkbd/blob/main/crkbd_rev1_via.hex))
3. Conecta cada mitad sin el cable TRRS, presiona el botón de reset y carga el firmware (usa un puerto USB 3.1, identificado por su color azul)
4. Descarga e instala [VIA](https://github.com/the-via/releases/releases) <- Lo puedes descargar directamente desde la pagina para sistemas operativos Windows y Mac

  
# 🎛️¿Qué incluye este firmware?
- Código optimizado para mostrar caracteres de bloqueo (Mayús y Num)
- ✅ Visualización de capas de función en pantallas.
- ✅ Imagen personalizada de Corne.
- Opciones de RGB activas para una mejor experiencia visual
- Funciones especiales habilitadas: Control de mouse, macros y multimedia

# Preparacion de QMK TOOLBOX
- Ejecuta QMK TOOLBOX como administrador
- Instala los drivers desde la pestaña TOOLS o con la combinación de teclas CTRL+N.
- Selecciona el firmware descargado desde la pestaña OPEN.
- En la opción MCU (AVR only), selecciona Atmega32U4 (necesario para controladores Arduino Pro Micro).
![Image](https://github.com/user-attachments/assets/5b23932c-b96d-4882-aa0a-739b7c6cdad7) 
