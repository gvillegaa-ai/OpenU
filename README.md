# 🌍 Plataforma de Gestión y Monitoreo Ambiental (OpenAQ & Wokwi)

Este proyecto consiste en una interfaz web interactiva de alto rendimiento (Dashboard) para la gestión, visualización y monitoreo de la calidad del aire y variables meteorológicas. Combina la estructura de la base de datos global de **OpenAQ** con simulaciones virtuales de dispositivos IoT (microcontroladores **ESP32** con sensores DHT22) configurados en el entorno de **Wokwi** para la ciudad de Quito, Ecuador.

---

## 🚀 Enlace del Proyecto en Producción

La plataforma se encuentra completamente funcional, desplegada y disponible de manera pública a través de **GitHub Pages**:

🔗 **[Visitar Plataforma de Monitoreo Ambiental](https://gvillegaa-ai.github.io/OpenU/)**

---

## 🛠️ Características del Dashboard

La aplicación está diseñada en un formato de tres columnas estructurado con **HTML5** y **CSS3** nativo (sin frameworks ni librerías de JS externas):

*   **Panel de Navegación Lateral (Izquierda):** Menú estructurado que permite la simulación de acceso a las distintas vistas del sistema (Dashboard, Gráfico en línea, Tarjetas de los sensores, Valores actuales, Tablas de datos y Alertas Activas).
*   **Sección Central de Monitoreo:**
    *   **Indicadores Clave (KPIs):** Resumen consolidado del sistema en tiempo real mostrando:
        *   `TOTAL DE DISPOSITIVOS`: **145** (Wokwi Sim.).
        *   `PROMEDIO GLOBAL DEL AIRE`: **52 índice** (Rango saludable).
        *   `ALERTAS ACTIVAS`: **0** alertas del sistema en curso.
    *   **Mapa de Ubicaciones:** Visualizador que posiciona geográficamente los sensores a nivel global, destacando en rojo la estación principal ubicada en Quito, Ecuador.
    *   **Tabla de Dispositivos IoT (Wokwi):** Monitoreo detallado de los sensores activos (`WOKWI_ESP32_01` al `04`), su última transmisión y su estado de conexión dinámico marcado en verde como **"Ao vivo"**.
*   **Ficha Técnica de la Ubicación (Derecha):** Desglose detallado del proveedor de datos (Red Nacional de Aire), tipo de estación virtual y gráficos simulados para variables históricas de 24 horas:
    *   Temperatura (DHT22)
    *   Humedad (DHT22)
    *   Calidad del Aire (Multi - Barra cromática de riesgo por CSS)

---

## ⚡ Tecnologías Implementadas

Para garantizar una carga ultra rápida, semántica limpia y un consumo mínimo de recursos, el desarrollo se ejecutó con estándares web puros:

*   **HTML5:** Estructuración semántica de componentes, contenedores y tablas.
*   **CSS3:** Maquetación moderna utilizando **CSS Flexbox** y **CSS Grid** para la alineación del diseño responsivo tricolumna, transiciones fluidas de interacción (`:hover`) y degradados dinámicos.
*   **FontAwesome (CDN):** Tipografía e iconos vectoriales de control para el dashboard.

---
