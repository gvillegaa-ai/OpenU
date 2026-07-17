# 🌍 Plataforma de Gestión y Monitoreo Ambiental (OpenAQ & Wokwi)

Este proyecto consiste en una interfaz de usuario interactiva (**Dashboard**) diseñada para la gestión, visualización y monitoreo de la calidad del aire y variables climatológicas. Combina datos de la API pública de **OpenAQ** con simulaciones virtuales de dispositivos IoT (microcontroladores **ESP32** con sensores DHT22) configurados en el entorno de **Wokwi** para la ciudad de Quito, Ecuador.

---

## 🚀 Características Principales

*   **Panel de Control Inteligente (KPIs):** Visualización del total de dispositivos virtuales (145), el promedio global del índice de calidad del aire (52) y un contador dinámico de alertas activas (0).
*   **Geolocalización Interactiva:** Un mapa intuitivo integrado que marca la ubicación exacta del sensor principal activo en Quito, Ecuador.
*   **Tabla de Monitoreo IoT:** Listado en tiempo real con el estado de transmisión de los dispositivos virtuales de Wokwi (`WOKWI_ESP32_01` al `04`), detallando el tipo de sensor, fecha, hora de transmisión y estado de conexión activo (*"Ao vivo"*).
*   **Ficha Técnica y Estadísticas:** Panel derecho que desglosa los sensores disponibles y muestra gráficos visuales de comportamiento histórico para las variables de Temperatura, Humedad y Calidad del Aire.

---

## 🛠️ Tecnologías Utilizadas

El desarrollo de este panel de control se ha realizado de manera nativa utilizando estándares web tradicionales, garantizando una carga rápida y un excelente rendimiento:

*   **HTML5:** Estructuración semántica de todo el contenido.
*   **CSS3:** Maquetación responsiva mediante Flexbox y CSS Grid, diseño de barras de datos personalizadas y transiciones interactivas.
*   **FontAwesome:** Biblioteca de iconos vectoriales para mejorar la estética visual.

---

## 💻 ¿Cómo ejecutar este proyecto localmente?

No necesitas instalar servidores, dependencias pesadas ni configurar bases de datos para probar la interfaz. Sigue estos pasos:

1. **Clona o descarga este repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/nombre-de-tu-repositorio.git](https://github.com/tu-usuario/nombre-de-tu-repositorio.git)
