# 🤖 Seguidor de Línea con Motor Eléctrico AC y Arduino

Este proyecto implementa un **seguidor de línea** utilizando **Arduino** para controlar un motor eléctrico de corriente alterna (AC). El sistema está diseñado para ser utilizado en el desarrollo de materiales y proyectos de **robótica**, donde el motor se activa y desactiva a través de botones, y el estado de este se indica mediante un LED. 

## 🧑‍💻 Autor
- **Giselle Ulloa** - [GitHub](https://github.com/GiselleUlloa)

## 🛠 Componentes Utilizados

- **Arduino UNO** o cualquier placa compatible.
- **Motor eléctrico AC** para movimiento.
- **Botones** para el arranque y paro del motor.
- **LED** para indicar el estado del motor.
- **Sensores de línea** (si se añaden, para el seguidor de línea).

## 🔌 Esquema de Conexión

1. **Pin 2**: Botón de arranque (entrada).
2. **Pin 3**: Botón de paro (entrada).
3. **Pin 13**: LED (salida) para indicar el estado del motor.

**Nota**: Este proyecto puede integrarse con sensores de línea para convertirlo en un robot seguidor de línea completo. Los sensores detectarán la línea en el suelo y guiarán el movimiento del robot.

## 📜 Descripción del Proyecto

Este proyecto tiene como objetivo controlar un motor eléctrico AC para un **seguidor de línea** básico. Aunque el proyecto no incluye los sensores de línea (que puedes agregar más adelante), el motor puede ser activado y detenido mediante botones, y el estado del motor se muestra en el LED conectado al pin 13.

### 💡 Funcionamiento:

1. **Botón de arranque**: Al presionar el botón de arranque, el motor se enciende y el LED se apaga. Esto indica que el robot está en movimiento.
2. **Botón de paro**: Al presionar el botón de paro, el motor se apaga y el LED se enciende, indicando que el robot se ha detenido.

En el futuro, puedes integrar sensores de línea (como los sensores IR) para hacer que el robot siga una línea en el suelo de manera autónoma.

### **Secuencia del Código:**
- Si el botón de **arranque** se presiona, el motor se enciende.
- El LED en el pin 13 se apaga cuando el motor está encendido.
- Si el botón de **paro** se presiona, el motor se apaga y el LED se enciende.

## ⚙️ Instrucciones

### Requisitos:

- **Arduino IDE** instalado.
- **Placa Arduino UNO** o compatible.
- **Cable USB** para conectar el Arduino a la computadora.
- **Sensores de línea** (opcional, para completar el seguidor de línea).

### Cómo usar el proyecto:

1. Conecta el **Arduino** a tu computadora mediante un **cable USB**.
2. **Carga el código** desde este repositorio en tu **Arduino IDE**.
3. Conecta los **botones** y el **LED** según el esquema de conexión descrito arriba.
4. Si deseas agregar la funcionalidad de seguidor de línea, conecta los **sensores de línea** al Arduino y adapta el código para leer los valores de los sensores y mover el motor en consecuencia.
5. **Presiona los botones** para controlar el motor. El LED indicará el estado de este.

### Configuración de pines:

1. **Pin 2**: Botón de arranque (entrada).
2. **Pin 3**: Botón de paro (entrada).
3. **Pin 13**: LED indicador (salida).

## 🚀 Próximos Pasos

Este proyecto es solo el comienzo. Para mejorar la funcionalidad y convertirlo en un **seguidor de línea completo**, puedes agregar **sensores de línea** IR para detectar la trayectoria y controlar el movimiento del robot. Además, puedes integrar otros sensores y motores para hacerlo más avanzado.

---

¡Gracias por revisar este proyecto! Si tienes alguna pregunta o sugerencia, no dudes en abrir un **Issue** o hacer un **Pull Request**.
