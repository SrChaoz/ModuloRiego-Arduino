# 🌱 Programador de Riego con Arduino Nano  

Este proyecto es un **programador de riego automático** basado en un **Arduino Nano**, diseñado para gestionar el riego de cultivos de manera eficiente. Utiliza un reloj **RTC DS3231** para programar los ciclos de riego y una pantalla **TFT LCD ILI9341** para la interfaz de usuario.  

## 📌 Componentes Utilizados  
### 🔹 Electrónicos  
- **⏰ DS3231** - Módulo reloj RTC para mantener la hora con precisión  
- **🔌 KBP307** - Puente rectificador 1000V 3A  
- **🔋 Capacitores** - 220μF, 1μF y 0.1mF  
- **🔹 Regulador Step-Down LM2596** - Para ajustar el voltaje de alimentación  

### 🔹 Control y Visualización  
- **💻 Arduino Nano** (ATmega328P)  
- **📟 Pantalla LCD TFT ILI9341 2.4"** - Interfaz gráfica para la configuración  
- **🎮 Joystick Analógico** - Navegación en la interfaz  
- **⚡ Relé de un módulo (10A)** - Para controlar la bomba de riego  

## 📜 Diagrama del Proyecto  
Aquí puedes ver el esquema de conexión del programador de riego:  

![Diseño Programador de Riego](https://github.com/user-attachments/assets/92c1671d-1e5b-4882-a2a6-c9858aa6d754)  

## 🚀 Cómo Usarlo  
1. **Configura la hora del RTC DS3231** con el código de inicialización  
2. **Ajusta los horarios de riego** a través de la pantalla TFT y el joystick  
3. **Conecta la bomba de riego** al relé para su activación automática  
4. **Disfruta del riego automatizado** y optimiza el consumo de agua  

---

✉️ **Contribuciones y mejoras son bienvenidas**. ¡Si tienes ideas, abre un issue o haz un pull request! 😃  


