# 🥊 UGP | Ultimate Grappling Promotion

<div align="center">

### Landing Page · Presentación de Plataforma de Eventos MMA

**Una propuesta digital para transformar la promoción y gestión de eventos de deportes de combate.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![Proyecto](https://img.shields.io/badge/Proyecto-SENA-39A900?style=flat-square)
![Tipo](https://img.shields.io/badge/Tipo-Landing_Page-2563EB?style=flat-square)
![Estado](https://img.shields.io/badge/Estado-Prototipo_Informativo-orange?style=flat-square)
![Responsive](https://img.shields.io/badge/Dise%C3%B1o-Responsive-8B5CF6?style=flat-square)

[📂 Repositorio](https://github.com/YurgenVelasco/ugp-landing-2-main) · [👨‍💻 Desarrollador](https://github.com/YurgenVelasco)

</div>

---

## 📖 Descripción general

**UGP — Ultimate Grappling Promotion** es una organización relacionada con la promoción de eventos de deportes de combate, como grappling y artes marciales mixtas (MMA).

Este repositorio contiene una **landing page informativa desarrollada como parte de un proyecto formativo del SENA**, cuyo propósito es presentar una propuesta de solución digital para apoyar la promoción y futura gestión de eventos deportivos.

La página comunica el contexto del proyecto, su propósito, las funcionalidades contempladas para una plataforma web y los beneficios potenciales para organizadores, participantes, patrocinadores y asistentes.

> **Importante:** Esta landing es una demostración informativa. No constituye la plataforma de boletería final y no procesa pagos, ventas, reservas reales ni validaciones de entradas.

---

## 🎯 Objetivo del proyecto

Presentar una propuesta de transformación digital para la gestión de eventos de deportes de combate mediante una experiencia web moderna, organizada y visualmente atractiva.

La iniciativa busca explorar cómo una plataforma digital podría facilitar:

- La promoción y difusión de eventos.
- La publicación de información relevante para los asistentes.
- La consulta de carteleras, fechas y ubicaciones.
- La organización de localidades y precios.
- La futura comercialización digital de entradas.
- La comunicación con patrocinadores.
- La administración de información relacionada con eventos y asistentes.

Estas capacidades corresponden a la visión del sistema completo, no necesariamente a funciones operativas de esta landing.

---

## 💡 ¿Qué problema busca resolver?

La organización de eventos deportivos involucra diferentes procesos que pueden resultar difíciles de coordinar cuando dependen de herramientas separadas.

Entre ellos se encuentran la publicación de información, la promoción de combates, la distribución de localidades, la comunicación con asistentes y la gestión de entradas.

La propuesta UGP plantea reunir estas necesidades en un ecosistema digital más organizado.

**La landing permite comunicar esa visión y presentar cómo podría funcionar la solución.**

---

## ✨ Características de la landing

### 🏠 Presentación del proyecto

Página de inicio con una identidad visual orientada a los deportes de combate, elementos gráficos y contenido introductorio.

### 🥋 Información de eventos

Presentación de eventos deportivos con datos de referencia, imágenes, fechas, ubicaciones y estados representados en la interfaz.

### 🎟️ Boletería informativa

Sección dedicada a mostrar localidades y precios de referencia.

**No permite comprar entradas ni realizar transacciones reales.**

### 🖼️ Galería y contenido visual

Espacios destinados a imágenes, recursos deportivos y material relacionado con los eventos.

### 🤝 Patrocinadores

Presentación visual de la propuesta de participación de marcas y aliados comerciales.

### 📊 Información dinámica

Generación de tarjetas, filtros, tablas y otros componentes utilizando JavaScript y datos definidos localmente.

### 📱 Diseño adaptable

La interfaz se ha diseñado para visualizarse en diferentes tamaños de pantalla, incluyendo computadores, tabletas y teléfonos móviles.

---

## 🧭 Secciones principales

| Sección | Propósito |
|---|---|
| Inicio | Presentar la identidad y el propósito de UGP |
| El proyecto | Explicar la propuesta de solución digital |
| Metodología | Mostrar el proceso planteado para gestionar eventos |
| Contenido | Presentar información relevante para asistentes |
| Comunidad | Explicar los perfiles relacionados con el sistema |
| Galería | Mostrar contenido visual |
| Actividades | Presentar eventos e historial de referencia |
| Boletería | Consultar localidades y precios demostrativos |
| Patrocinio | Presentar oportunidades para aliados |
| Plataforma | Describir el problema y la solución |
| Alcance | Exponer las funcionalidades contempladas |
| Contacto | Mostrar los canales de comunicación del proyecto |

---

## 🛠️ Tecnologías utilizadas

<div align="center">

| Tecnología | Aplicación |
|---|---|
| **HTML5** | Estructura semántica del contenido |
| **CSS3** | Estilos, componentes y efectos visuales |
| **JavaScript** | Interactividad, filtros y renderización dinámica |
| **Google Fonts** | Tipografías de la interfaz |
| **SVG** | Recursos gráficos escalables |
| **IntersectionObserver** | Animaciones relacionadas con la visualización de elementos |

</div>

### Características técnicas

- Desarrollo frontend sin frameworks.
- Sin dependencias de Node.js.
- Sin procesos de compilación.
- Sin conexión a base de datos.
- Sin backend implementado en esta landing.
- Ejecución mediante archivos estáticos.
- Separación entre estructura, estilos y datos dinámicos.

El proyecto utiliza **JavaScript puro (Vanilla JavaScript)**, sin React, Vue ni Angular.

---

## 🏗️ Arquitectura de la landing

La implementación organiza los archivos según sus responsabilidades principales.

```text id="e3v9kf"
                  NAVEGADOR
                      |
                      v
                 index.html
                      |
          +-----------+-----------+
          |                       |
          v                       v
    css/style.css             JavaScript
          |                       |
          |                 +-----+-----+
          |                 |           |
          v                 v           v
    Presentación        js/data.js   js/ui.js
    y estilos               |           |
                            +-----+-----+
                                  |
                                  v
                       Componentes dinámicos
```

**Responsabilidades:**

- `index.html`: estructura principal de la landing.
- `css/style.css`: identidad visual, diseño adaptable y componentes.
- `js/data.js`: información utilizada por la interfaz.
- `js/ui.js`: filtros, tarjetas, tablas y animaciones.

Esta arquitectura corresponde exclusivamente al frontend informativo publicado en el repositorio.

---

## 📁 Estructura del repositorio

```text id="g8beqh"
ugp-landing-2-main/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── data.js
│   ├── ui.js
│   └── hero-3d.js
│
├── assets/
│   ├── images/
│   │   ├── branding/
│   │   ├── events/
│   │   ├── fighters/
│   │   ├── maps/
│   │   └── sponsors/
│   │
│   └── vendor/
│       └── three.min.js
│
└── README.md
```

### Organización del código

| Archivo o carpeta | Descripción |
|---|---|
| `index.html` | Estructura de la página |
| `css/style.css` | Estilos, variables y componentes visuales |
| `js/data.js` | Datos de eventos, precios y funcionalidades |
| `js/ui.js` | Interacciones y generación de elementos |
| `js/hero-3d.js` | Código anterior de una experiencia 3D |
| `assets/images/` | Recursos gráficos organizados por categoría |
| `assets/vendor/` | Recursos de bibliotecas conservados |

**Nota:** el código 3D anterior y la biblioteca Three.js se conservan como recursos, pero no participan en la portada actual.

---

## 🎨 Identidad visual

La interfaz utiliza una estética inspirada en deportes de combate, con contrastes intensos, fondos oscuros y elementos gráficos de impacto.

### Paleta de colores

| Color | Código HEX | Aplicación |
|---|---|---|
| Negro carbón | `#101010` | Fondos principales |
| Gris oscuro | `#242424` | Superficies secundarias |
| Rojo vino | `#8E1F2D` | Acentos visuales |
| Rojo intenso | `#F04438` | Elementos destacados |
| Naranja | `#FF7518` | Efectos de impacto |
| Morado oscuro | `#24152F` | Ambientación |
| Blanco | `#F5F5F5` | Textos y contrastes |

### Tipografías

**Bebas Neue**

Utilizada para títulos, encabezados y elementos de mayor impacto visual.

**Montserrat**

Empleada para párrafos, navegación y contenido informativo.

### Recursos gráficos

El proyecto incorpora elementos visuales como:

- Emblema de UGP.
- Ilustraciones de puños deportivos.
- Efectos de pintura roja.
- Destellos e impactos gráficos.
- Fotografías relacionadas con eventos y combatientes.
- Flyers y elementos promocionales.

Estos recursos ayudan a construir una identidad visual coherente con la temática del proyecto.

---

## ⚙️ Funcionamiento del contenido dinámico

La landing separa parte de la información del código encargado de mostrarla.

### `js/data.js`

Contiene estructuras de datos utilizadas para generar contenido en la interfaz.

Entre ellas se encuentran:

| Estructura | Contenido |
|---|---|
| `DATA.events` | Eventos, fechas, ubicaciones, imágenes y estados |
| `DATA.stateLabel` | Etiquetas visibles de los estados |
| `DATA.prices` | Localidades y precios de referencia |
| `DATA.features` | Funcionalidades contempladas para el sistema |

### `js/ui.js`

Utiliza los datos definidos para construir y actualizar elementos visuales.

Incluye lógica relacionada con:

- Filtros de información.
- Tarjetas dinámicas.
- Tablas.
- Representación de estados.
- Animaciones de entrada.

### Orden de carga

```text id="skv3ax"
data.js → ui.js
```

Este orden permite que la información esté disponible antes de ejecutar las funciones que la utilizan.

---

## 📱 Diseño responsive y accesibilidad

La landing contempla diferentes aspectos para mejorar la experiencia de navegación.

### Diseño adaptable

- Distribución ajustable según el tamaño de pantalla.
- Navegación para dispositivos móviles.
- Organización de contenido mediante componentes visuales.
- Uso de recursos escalables.

### Accesibilidad

- Textos alternativos para imágenes informativas.
- Identificación de elementos decorativos.
- Consideración de las preferencias de movimiento reducido.
- Colores organizados mediante variables CSS.
- Animaciones mediante `IntersectionObserver`.

Estas características representan las prácticas aplicadas en la interfaz y no sustituyen una auditoría formal de accesibilidad.

---

## 🚀 Instalación y ejecución

La landing puede ejecutarse directamente en un navegador moderno.

### Requisitos

- Navegador web actualizado.
- Git, si desea clonar el repositorio.
- Editor de código opcional.

### 1. Clonar el repositorio

```bash id="c3wq6n"
git clone https://github.com/YurgenVelasco/ugp-landing-2-main.git
```

### 2. Acceder al directorio

```bash id="kz2nwa"
cd ugp-landing-2-main
```

### 3. Ejecutar

Abra `index.html` en el navegador.

También puede utilizar la extensión **Live Server** de Visual Studio Code.

### 4. Explorar

Navegue por las secciones de la landing para conocer el proyecto, consultar información demostrativa y explorar su propuesta.

**No se requiere instalar paquetes, configurar servicios ni conectar bases de datos.**

---

## 🔮 Visión del sistema completo

La landing forma parte de la presentación de una iniciativa más amplia.

El sistema proyectado busca contemplar funcionalidades como:

### 🎫 Gestión de entradas

- Consulta de eventos disponibles.
- Selección de localidades.
- Gestión de entradas.
- Emisión de tickets digitales.

### 💳 Integración de pagos

Se contempla la integración con servicios de pagos en línea como Wompi.

### 📲 Validación de accesos

Se proyecta utilizar códigos QR para apoyar el control de entradas.

### 👥 Gestión de usuarios

Administración de perfiles y permisos según las responsabilidades de cada usuario.

### 🥊 Administración de eventos

Gestión de información deportiva, participantes, carteleras y datos administrativos.

**Estas funcionalidades representan la visión del sistema completo y no están implementadas operativamente dentro de esta landing.**

---

## ⚠️ Estado actual y limitaciones

**Estado:** prototipo informativo frontend.

La implementación publicada en este repositorio:

- No contiene un backend.
- No dispone de autenticación real.
- No utiliza una base de datos conectada.
- No procesa pagos.
- No vende entradas reales.
- No genera tickets QR operativos.
- No permite administrar eventos desde un panel funcional.
- Utiliza información de referencia para presentar el proyecto.

La landing sirve como demostración visual y explicación de una propuesta tecnológica, no como sistema comercial de boletería.

---

## 🗺️ Posibles mejoras

- [ ] Publicar una demostración mediante GitHub Pages.
- [ ] Incorporar capturas de pantalla al README.
- [ ] Mejorar las pruebas de compatibilidad entre navegadores.
- [ ] Realizar una auditoría de accesibilidad.
- [ ] Agregar pruebas automatizadas para las funcionalidades interactivas.
- [ ] Mejorar la documentación de los datos de ejemplo.
- [ ] Incorporar controles para validar la información demostrativa.
- [ ] Optimizar recursos gráficos y tiempos de carga.
- [ ] Mantener actualizada la presentación según evolucione el sistema principal.

---

## 👨‍💻 Autor

<div align="center">

### Yurgen Andrey Velasco Rojas

**Aprendiz de Análisis y Desarrollo de Software (ADSO) — SENA**

Desarrollador de software en formación con interés en backend, arquitectura de aplicaciones, bases de datos y tecnologías web.

[![GitHub](https://img.shields.io/badge/GitHub-YurgenVelasco-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YurgenVelasco)

</div>

---

## 📄 Derechos de autor y recursos

Este proyecto tiene fines académicos y demostrativos.

No se declara una licencia de software abierta para este repositorio.

La identidad de UGP y los recursos de terceros deben utilizarse respetando las autorizaciones y derechos correspondientes.

La publicación del repositorio no implica la concesión de derechos sobre marcas, imágenes o recursos protegidos.

---

## 💭 Reflexión

Este proyecto representa una experiencia de aprendizaje en diseño de interfaces, organización de contenido y presentación de soluciones de software.

Su desarrollo permite explorar cómo una propuesta tecnológica puede comunicarse de forma visual y comprensible antes de convertirse en un sistema completo.

**Una buena solución comienza por comprender el problema y comunicar claramente su propósito.**

---

<div align="center">

### 🥊 UGP — La experiencia comienza antes del combate.

**Proyecto formativo desarrollado con creatividad, dedicación y tecnología.**

[📂 Repositorio](https://github.com/YurgenVelasco/ugp-landing-2-main) · [👨‍💻 Desarrollador](https://github.com/YurgenVelasco)

</div>
