# 📚 AlphaKids PRO v15.0

**AlphaKids PRO** es un ecosistema educativo interactivo diseñado para el aprendizaje fonético avanzado en niños. Utiliza una interfaz de alto impacto basada en **Glassmorphism**, optimizada para dispositivos táctiles y enfocada en la eliminación de distracciones visuales.

## 🚀 Características Principales

*   **Protocolo de Blindaje Visual:** Interfaz inmersiva sin barras de desplazamiento (Zero-Scrollbar) y adaptada a `viewport-fit=cover`.
*   **Aprendizaje Fonético Completo:** Ciclo de sílabas asociadas a palabras completas (ej. B -> Bicicleta), eliminando abreviaturas disonantes.
*   **Motor de Voz Hiper-Natural:** Síntesis de voz optimizada para la pronunciación clara de fonemas y palabras.
*   **Multi-Tipografía:** Soporte dinámico para Mayúsculas, Minúsculas y Cursiva (enfocada en caligrafía).
*   **PWA Premium (Progressive Web App):** 
    *   **Instalación Directa:** Botón nativo integrado para instalar en la pantalla de inicio sin usar los menús del navegador.
    *   **Acceso Offline:** Funcionamiento sin conexión mediante Service Workers.
    *   **Flash Logo Entry:** Animación de carga profesional al iniciar la app.

## 🛠️ Tecnologías Utilizadas

*   **Frontend:** Vanilla JavaScript, HTML5 (Semántico), CSS3 (Custom Properties & Flexbox/Grid).
*   **Diseño:** Glassmorphism UI, Dark Mode Premium.
*   **PWA Core:** Web App Manifest y Service Worker API.
*   **Audio:** Web Speech API (SpeechSynthesis).

## 📦 Estructura del Proyecto

```text
├── index.html      # Núcleo del sistema y lógica de UI
├── manifest.json   # Configuración de instalación PWA
└── sw.js           # Service Worker para gestión de caché y offline