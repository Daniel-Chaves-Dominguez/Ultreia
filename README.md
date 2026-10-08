<div align="center">

<img src="https://res.cloudinary.com/daul6tzck/image/upload/v1791113078/image_ubfnbw.png" alt="Logo Ultreia" width="140">

# Ultreia

### El Camino lo hacemos entre todos

Plataforma web comunitaria que conecta a peregrinos del Camino de Santiago con vecinos, voluntarios y negocios locales para que nadie haga el Camino solo.

[🌐 Ver la web desplegada](#-web-desplegada-en-vercel) · [🎨 Diseño en Figma](#-diseño-en-figma) · [👥 Equipo](#-equipo)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📌 ¿Qué es Ultreia?

**Ultreia** es una web de apoyo comunitario para el Camino de Santiago. Su nombre viene del saludo medieval de los peregrinos: uno decía *«¡Ultreia!»* (¡más allá!) y el otro respondía *«¡Et suseia!»* (¡y más arriba!).

### ❓ ¿Qué problema soluciona?

Durante el Camino, los peregrinos se encuentran con problemas que no siempre saben a quién comunicar: una fuente sin agua, un tramo cortado, una lesión, no encontrar alojamiento o simplemente no querer caminar solos. Además, la información sobre recursos (alojamientos, servicios, accesibilidad, mascotas...) está muy dispersa.

### ✅ Funcionalidad principal

Ultreia reúne en un único sitio a **quien necesita ayuda** y a **quien puede ofrecerla**:

- **Pedir ayuda** o **informar de incidencias** en el Camino.
- **Ofrecer** alojamiento, comida, servicios o espacios para peregrinos.
- **Participar** como voluntario en iniciativas.
- **Encontrar compañeros** de ruta.
- **Consultar** recursos en el mapa y las publicaciones del tablón comunitario.
- **Contactar** con teléfonos de emergencia y un chat de preguntas frecuentes.

---

## 🌐 Web desplegada en Vercel

La web está publicada en **Vercel** y se puede visitar aquí:

👉 **[https://ENLACE-DE-VERCEL.vercel.app](https://ENLACE-DE-VERCEL.vercel.app)**

> El despliegue está conectado al repositorio de GitHub: cada cambio que se sube a la rama `main` se publica automáticamente.

---

## 📸 Así se ve la web desplegada

### Página de inicio

![Página de inicio de Ultreia](ruta/captura-inicio.png)

### Hero y saludo del peregrino

![Hero de Ultreia](ruta/captura-hero.png)

### ¿Qué necesitas? y áreas de impacto

![Tarjetas de áreas de impacto](ruta/captura-areas.png)

### Tablón comunitario y mapa

![Tablón comunitario y mapa](ruta/captura-tablon-mapa.png)

### Página de contacto y ayuda

![Página de contacto](ruta/captura-contacto.png)

### Versión móvil

<p align="center">
  <img src="ruta/captura-movil-1.png" alt="Versión móvil 1" width="250">
  <img src="ruta/captura-movil-2.png" alt="Versión móvil 2" width="250">
</p>

---

## 🎨 Diseño en Figma

Antes de programar, diseñamos la web en **Figma** siguiendo la metodología de **Atomic Design** (átomos, moléculas, organismos y páginas).

🔗 **[Ver el diseño en Figma](https://www.figma.com/design/3qCr2xarjgeDtZd6AghsSY/Ultreia?node-id=6-5&t=gLfOmk1ekCxSwrUW-0)**

### Tipografía

- **Plus Jakarta Sans** → tipografía principal (pesos 400 a 800).
- **Caveat** → detalles manuscritos.

---

## 🛠️ Stack utilizado

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura semántica de las páginas |
| **CSS3** | Estilos, maquetación, animaciones y diseño responsive |
| **Figma** | Diseño de la interfaz y prototipo |
| **Trello** | Organización de tareas del equipo |
| **Git y GitHub** | Control de versiones y trabajo en equipo por ramas |
| **Vercel** | Despliegue de la web |
| **Cloudinary** | Alojamiento de las imágenes |

> 💡 El proyecto está hecho **solo con HTML y CSS, sin JavaScript**. Todas las interacciones (tarjetas que giran, chat de preguntas, animaciones) están resueltas con CSS.

### 📚 Librerías y recursos externos

| Librería | ¿Por qué la elegimos? |
|---|---|
| **[Google Fonts](https://fonts.google.com/)** | Para cargar Plus Jakarta Sans y Caveat de forma rápida y gratuita. |
| **[Remix Icon](https://remixicon.com/)** | Iconos modernos y limpios que encajan con el estilo de la web (tarjetas, flechas, avisos). |
| **[Font Awesome](https://fontawesome.com/)** | Iconos de redes sociales para el footer. |
| **[Cloudinary](https://cloudinary.com/)** | Para alojar las imágenes en la nube y no cargar el repositorio con archivos pesados. |

---

## 🏗️ Arquitectura del proyecto

```
Ultreia/
├── index.html      → Página principal
├── contact.html    → Página de contacto y ayuda
├── styles.css      → Hoja de estilos compartida por todas las páginas
└── README.md       → Documentación del proyecto
```

### Secciones de la página principal

| Sección | Descripción |
|---|---|
| **Nav** | Logo, menú de navegación y botones de acceso |
| **Hero** | Imagen principal con el lema *«El Camino lo hacemos entre todos»* |
| **Saludo del peregrino** | Explicación del origen del nombre Ultreia |
| **¿Qué necesitas?** | Cuatro accesos rápidos: necesito ayuda, quiero ayudar, quiero ofrecer y no camino solo |
| **Áreas de impacto** | Ocho tarjetas que giran al pasar el ratón con información de cada área |
| **Tablón comunitario y mapa** | Últimas publicaciones de la comunidad y mapa de recursos |
| **Incidencias** | Llamada a la acción para informar de problemas en el Camino |
| **Footer** | Navegación, áreas, información legal y créditos |

### Página de contacto

| Sección | Descripción |
|---|---|
| **Cabecera** | *«Estamos contigo en el Camino»* |
| **Teléfonos de emergencia** | 112, 062, 091 y 061 |
| **Chat Ultreia** | Preguntas frecuentes desplegables hechas con `<details>` y `<summary>` |
| **Otras formas de contactar** | Teléfono, correo y horario |

---

## ✨ Buenas prácticas aplicadas

- **HTML semántico**: uso de `<header>`, `<section>`, `<footer>`, `<details>`...
- **Accesibilidad**: textos alternativos (`alt`) en las imágenes y `aria-label` en los iconos de redes sociales.
- **Nomenclatura en camelCase** para todas las clases (`navMenu`, `heroTitle`...).
- **CSS organizado por secciones**, con comentarios que indican cada bloque.
- **Diseño responsive** con *Flexbox*, *CSS Grid* y *media queries* para móvil, tablet y escritorio.
- **Animaciones con CSS puro**: `@keyframes`, `transition` y `transform`.
- **Ramas y commits en inglés**, con mensajes claros que describen cada cambio.
- **Imágenes optimizadas** y alojadas en Cloudinary.

---

## 🚀 Instalación y uso

Este proyecto **no necesita instalar dependencias** ni archivo `.env`, porque es una web estática con HTML y CSS.

### 1. Clonar el repositorio

```bash
git clone https://github.com/Daniel-Chaves-Dominguez/Ultreia.git
cd Ultreia
```

### 2. Abrir el proyecto

**Opción A · Con Visual Studio Code y Live Server (recomendado)**

1. Abre la carpeta del proyecto en **VS Code**.
2. Instala la extensión **Live Server**.
3. Haz clic derecho en `index.html` → **Open with Live Server**.

**Opción B · Directamente en el navegador**

Haz doble clic en `index.html`.

> ⚠️ Necesitas conexión a internet para que carguen las fuentes, los iconos y las imágenes, que se sirven desde Google Fonts, Remix Icon, Font Awesome y Cloudinary.

---

## 🌿 Control de versiones

Trabajamos con **Git y GitHub**, con **una rama por cada sección** de la web. Cuando una sección estaba terminada, se unía a `main`.

| Rama | Sección | Responsable |
|---|---|---|
| `navbar` | Navegación | Alba |
| `hero` | Hero | Alba |
| `pilgrimGreeting` | Saludo del peregrino | Daniel |
| `whatDoYouNeed` | ¿Qué necesitas? | Daniel |
| `cards` | Áreas de impacto | Melissa |
| `community-board` | Tablón comunitario y mapa | Alba |
| `incident` | Incidencias | Daniel |
| `footer` | Footer | Melissa |

**Flujo que hemos seguido:**

```
main
 ├── navbar
 ├── hero
 ├── pilgrimGreeting
 ├── ...
 └── footer
```

```bash
git checkout main
git pull
git checkout -b nombre-de-la-rama
# ...cambios...
git add .
git commit -m "Add navbar with logo, menu and buttons"
git push -u origin nombre-de-la-rama
```

### ⚠️ Mejora detectada

Creamos las ramas de cada sección **directamente desde `main`**. Lo correcto habría sido usar una rama intermedia **`dev`** (desarrollo), de forma que `main` solo reciba versiones estables y revisadas:

```
main  ← solo versiones estables
 └── dev  ← aquí se integran y prueban las secciones
      ├── navbar
      ├── hero
      ├── ...
      └── footer
```

Así, si algo falla al unir una sección, el error se queda en `dev` y la web publicada en `main` (y en Vercel) no se rompe. Lo aplicaremos en los próximos proyectos.

---

## 📋 Metodología

Seguimos una metodología **ágil inspirada en Scrum**:

- **Trello** para organizar las tareas en columnas (*Pendiente*, *En proceso*, *Hecho*).
- **Reparto de tareas por secciones**, para que cada miembro trabajara en paralelo sin pisar el trabajo de los demás.
- **Revisiones en equipo** antes de unir cada rama a `main`.

🔗 **[Ver el tablero de Trello](https://trello.com/b/A9NZHmCw/ultreia)**

---

## 🧠 Lo aprendido

- Trabajar en equipo con **Git y GitHub usando ramas**, y resolver conflictos.
- La importancia de tener una rama **`dev`** entre `main` y las ramas de trabajo, para proteger la versión publicada.
- Pasar un diseño de **Figma a código** respetando colores, tipografía y espaciados.
- Crear **interacciones y animaciones solo con CSS**, sin JavaScript.
- Maquetar con **Flexbox y Grid** y adaptar la web a distintas pantallas.
- Organizar el código con una **nomenclatura común** (camelCase) para que todo el equipo lo entienda.
- **Desplegar** una web en Vercel.

---

## 🔭 Próximos pasos

- [ ] Trabajar con el flujo **`main` → `dev` → ramas de trabajo**.
- [ ] Añadir **JavaScript** para que los filtros del mapa y el chat sean interactivos.
- [ ] Conectar los formularios a un **back-end** para guardar solicitudes e incidencias.
- [ ] Integrar un **mapa interactivo** real con la ubicación de los recursos.
- [ ] Crear un **sistema de usuarios** para publicar en el tablón comunitario.
- [ ] Traducir la web a otros idiomas (**inglés, gallego, portugués**), pensando en peregrinos de todo el mundo.
- [ ] Mejorar la **accesibilidad** con pruebas de contraste y navegación por teclado.

---

## 👥 Equipo

| | Nombre | LinkedIn |
|---|---|---|
| 👩‍💻 | **Alba Ruiz de la Vega** | [LinkedIn](https://www.linkedin.com/in/alba-ruiz-de-la-vega-765b21384/) |
| 👨‍💻 | **Daniel Chaves Domínguez** | [LinkedIn](URL_LINKEDIN_DANIEL) |
| 👩‍💻 | **Melissa Guerrero** | [LinkedIn](https://www.linkedin.com/in/melissafguerreroc/) |

---

<div align="center">

**¡Ultreia et suseia!** 🐚

© 2026 Ultreia. Todos los derechos reservados.

</div>
