# LED Lamp Meter

Este proyecto consiste en un medidor de consumo, voltaje y potencia para lámparas LED. El dispositivo está diseñado para ayudar a monitorear el rendimiento y la eficiencia energética de las lámparas LED, proporcionando datos precisos y en tiempo real.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribución](#contribución)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Descripción

El medidor de lámparas LED es una herramienta que mide el consumo de energía, el voltaje y la potencia de lámparas LED. Este dispositivo es útil para:

- Analizar el rendimiento de diferentes modelos de lámparas LED.
- Optimizar el uso de energía en instalaciones de iluminación.
- Detectar problemas de eficiencia en el uso de lámparas LED.

## Características

- **Medición de Consumo**: Monitorea el consumo de energía en tiempo real.
- **Medición de Voltaje**: Mide el voltaje de entrada de las lámparas LED.
- **Medición de Potencia**: Calcula la potencia utilizada por las lámparas LED.
- **Interfaz de Usuario**: Pantalla LCD para mostrar las lecturas en tiempo real.
- **Conectividad**: Opciones para conexión a una aplicación móvil o web para el monitoreo remoto.

## Instalación

1. **Requisitos de Hardware**:
   - Sensores de voltaje y corriente.
   - Microcontrolador (Arduino, ESP32, etc.).
   - Pantalla LCD.
   - Conectores y cables.

2. **Requisitos de Software**:
   - [Arduino IDE](https://www.arduino.cc/en/software)
   - Bibliotecas necesarias:
     - `Wire.h`
     - `LiquidCrystal_I2C.h`

3. **Pasos de Instalación**:
   - Conectar los sensores de voltaje y corriente al microcontrolador.
   - Conectar la pantalla LCD al microcontrolador.
   - Subir el código al microcontrolador usando el Arduino IDE.
   - Alimentar el dispositivo y comenzar las mediciones.

## Uso

1. **Encender el Dispositivo**:
   - Conectar la fuente de alimentación al medidor.
   - Verificar que la pantalla LCD se encienda y muestre las lecturas iniciales.

2. **Realizar Mediciones**:
   - Conectar la lámpara LED al medidor.
   - Observar las lecturas de consumo, voltaje y potencia en la pantalla LCD.

3. **Opcional: Monitoreo Remoto**:
   - Conectar el dispositivo a la red Wi-Fi (si está habilitado).
   - Acceder a la aplicación móvil o web para monitorear las lecturas remotamente.

## Contribución

¡Las contribuciones son bienvenidas! Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-característica`).
3. Realiza los cambios y haz commit (`git commit -am 'Añadir nueva característica'`).
4. Empuja la rama (`git push origin feature/nueva-característica`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).

## Contacto

Para preguntas o sugerencias, por favor contacta a [tu-nombre] a través de [tu-email@example.com].

---

¡Gracias por usar nuestro medidor de lámparas LED!
