# 🤖 Proyecto Turing Bots 🚀

¡Bienvenido al proyecto **Turing Bots**\! Este repositorio contiene el código fuente para el sitio web de una empresa dedicada a ofrecer soluciones de automatización mediante bots, incluyendo agentes de IA y chatbots programados para diversas plataformas como WhatsApp, Instagram y Facebook Messenger.

El objetivo principal de este sitio web es presentar los servicios de Turing Bots, brindar información sobre la empresa, y facilitar el contacto con clientes potenciales.

## 📁 Estructura del Proyecto

El proyecto está organizado de manera intuitiva para una fácil navegación y mantenimiento:

```
.
├── src/
│   ├── asset/              # Contiene recursos como imágenes y logotipos
│   │   ├── Logotype.svg
│   │   └── images/
│   ├── js/                 # Archivos JavaScript
│   │   └── script.js
│   └── styles/             # Hojas de estilo CSS
│       ├── style.css
│       └── style_empresa.css
├── empresa.html            # Página "Nosotros" con información de la empresa, misión, visión y equipo.
├── gracias.html            # Página de agradecimiento post-contacto.
├── index.html              # Página principal (Home) del sitio web.
├── politica_privacidad.html# Página con la política de privacidad.
└── terminos.html           # Página con los términos de servicio.
```

## 💻 Tecnologías Utilizadas

Este proyecto web está construido con un enfoque en la simplicidad y la compatibilidad, utilizando las siguientes tecnologías estándar:

* **HTML5**: Para la estructura y el contenido semántico de las páginas web.
* **CSS3**: Para el diseño visual, la tipografía, los colores (con variables CSS) y la adaptación a diferentes tamaños de pantalla (diseño responsivo). Se utilizan `@import` para modularizar los estilos.
* **JavaScript**: Para añadir interactividad a la interfaz de usuario, como la gestión del menú móvil y la funcionalidad de modales para detalles de servicios.
* **Google Fonts (Montserrat, Inter)**: Para una tipografía moderna y atractiva.
* **Font Awesome**: Para iconos escalables y personalizables.

## ✨ Características Clave

El sitio web de Turing Bots ofrece las siguientes funcionalidades y secciones principales:

* **Página Principal (`index.html`)**:
  * **Hero Section**: Presentación impactante con el lema "Automatizamos tu éxito" y una breve descripción de las soluciones de bots.
  * **Nuestros Servicios**: Descripción detallada de los tipos de bots ofrecidos:
    * **Agentes de IA**: Con conversación abierta, comprensión de lenguaje natural, respuestas contextuales y entrenamiento personalizado. Ideal para soporte avanzado y atención 24/7.
    * **Chatbots Programados**: Menús interactivos, respuestas rápidas, derivación a agentes humanos y respuestas predefinidas. Ideal para atención básica, reservas y preguntas frecuentes.
    * **Asistencia 360°; Redes Sociales**: Para gestionar consultas frecuentes y promociones en plataformas como Instagram y Facebook. Incluye respuestas automáticas, menús con botones, mensajes fuera de horario y activación por palabras clave.
    * **Bots para Páginas Web**: Chatbots inteligentes para sitios web, con integración a formularios de contacto, respuestas a preguntas frecuentes y soporte en línea.
  * **Sección "Nosotros" (enlazada a `empresa.html`)**.
  * **Sección de Proyectos Destacados y Testimonios de Clientes**.
  * **Formulario de Contacto**.
* **Página "Empresa" (`empresa.html`)**:
  * **Hero Section**: Con el título "Conoce más sobre Turing".
  * **Sección "Nosotros"**: Información sobre la visión de la empresa.
  * **Misión, Visión y Valores**: Detalles sobre los principios fundamentales de Turing Bots.
  * **Nuestro Equipo**: Presentación de los miembros clave del equipo con sus roles.
* **Página "Política de Privacidad" (`politica_privacidad.html`)**: Contiene información detallada sobre el uso y protección de datos personales.
* **Página "Términos de Servicio" (`terminos.html`)**: Establece las condiciones legales para el uso de los servicios de Turing Bots.
* **Página "Gracias" (`gracias.html`)**: Una página de confirmación que aparece después de enviar un formulario de contacto, agradeciendo al usuario. Incluye estilos CSS incrustados para un diseño específico de agradecimiento.

### Funcionalidades Interactivas:

* **Modal de Servicios**: Al hacer clic en "Más Información" para un servicio específico (ej. "Bot para WhatsApp (sin IA)"), se abre un modal con detalles adicionales como funcionalidades, procesos de desarrollo, tiempo de entrega estimado y garantía.
* **Menú de Navegación Responsivo**: El encabezado incluye un menú de navegación principal con enlaces a las diferentes secciones del sitio. En dispositivos móviles, un botón de "hamburguesa" alterna la visibilidad del menú.
* **Efectos de Animación CSS**: Elementos como la sección Hero y las tarjetas de equipo presentan animaciones suaves como `fadeInUp`.

---

**© 2025 Turing Bots. Todos los derechos reservados.**
