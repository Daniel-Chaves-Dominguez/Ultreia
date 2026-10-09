<div align="center">

<img src="https://res.cloudinary.com/daul6tzck/image/upload/v1791113078/image_ubfnbw.png" alt="Ultreia logo" width="140">

# Ultreia

### We walk the Camino together

A community web platform that connects pilgrims on the Camino de Santiago with locals, volunteers and local businesses, so that no one walks the Camino alone.

[ Live demo](#-live-demo-on-vercel) · [ Figma design](#-figma-design) · [ Team](#-team)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/Daniel-Chaves-Dominguez/Ultreia/blob/main/index.html)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/Daniel-Chaves-Dominguez/Ultreia/blob/main/styles.css)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/3qCr2xarjgeDtZd6AghsSY/Ultreia?node-id=0-1&p=f&t=Fk0yzKOQ2sBhyMlp-0)
[![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)](https://trello.com/b/A9NZHmCw/ultreia)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://ultreia-eight.vercel.app)

</div>

---

##  What is Ultreia?

**Ultreia** is a community support website for the Camino de Santiago. Its name comes from the medieval pilgrims' greeting: one would say *"Ultreia!"* (further!) and the other would reply *"Et suseia!"* (and higher!).

###  What problem does it solve?

Along the Camino, pilgrims face problems they don't always know who to report to: a fountain with no water, a closed path, an injury, not finding accommodation or simply not wanting to walk alone. On top of that, information about resources (accommodation, services, accessibility, pets...) is scattered across many places.

###  Main features

Ultreia brings together in one place **those who need help** and **those who can offer it**:

- **Ask for help** or **report incidents** on the Camino.
- **Offer** accommodation, food, services or spaces for pilgrims.
- **Take part** as a volunteer in local initiatives.
- **Find walking companions**.
- **Browse** resources on the map and posts on the community board.
- **Get in touch** through emergency numbers and a FAQ chat.

---

##  Live demo on Vercel

The website is deployed on **Vercel** and can be visited here:

 **[https://ultreia-eight.vercel.app](https://ultreia-eight.vercel.app)**

> The deployment is connected to the GitHub repository: every change pushed to the `main` branch is published automatically.

---

##  Screenshots of the deployed site

### Home page with the hero and the pilgrim's greeting

![Ultreia home page](https://res.cloudinary.com/duzljw2pp/image/upload/v1791450816/Captura_de_pantalla_2026-10-08_110606_chbfbv.png)

### What do you need?

![What do you need section](https://res.cloudinary.com/duzljw2pp/image/upload/v1791451008/Captura_de_pantalla_2026-10-08_111639_v8xgz7.png)

### Our 8 impact areas

![Impact areas section](https://res.cloudinary.com/duzljw2pp/image/upload/v1791529521/Captura_de_pantalla_2026-10-09_090426_u5qvti.png)

### Community board and map

![Community board and map](https://res.cloudinary.com/duzljw2pp/image/upload/v1791451215/Captura_de_pantalla_2026-10-08_112007_rlyuec.png)

### Incident reporting and footer

![Incident reporting and footer](https://res.cloudinary.com/duzljw2pp/image/upload/v1791451319/Captura_de_pantalla_2026-10-08_112152_q2f1kz.png)

### Contact and help page

![Contact page](https://res.cloudinary.com/duzljw2pp/image/upload/v1791455264/Captura_de_pantalla_2026-10-08_122722_auim1c.png)

### Legal information page

![Legal information page](https://res.cloudinary.com/duzljw2pp/image/upload/v1791529537/Captura_de_pantalla_2026-10-09_090506_lntvjm.png)

---

##  Figma design

Before writing any code, we designed the website in **Figma** following the **Atomic Design** methodology (atoms, molecules, organisms and pages).

 **[View the design in Figma]([(https://www.figma.com/design/3qCr2xarjgeDtZd6AghsSY/Ultreia?node-id=58-126&t=UQYLRJXZNWBsbbef-1)]**

### Typography

- **Plus Jakarta Sans** → main typeface (weights 400 to 800).
- **Caveat** → handwritten details.

---

##  Tech stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, layout, animations and responsive design |
| **Figma** | Interface design and prototype |
| **Trello** | Team task management |
| **Git & GitHub** | Version control and branch-based teamwork |
| **Vercel** | Website deployment |
| **Cloudinary** | Image hosting |

>  The project is built **with HTML and CSS only, no JavaScript**. All interactions (flip cards, FAQ chat, animations) are handled with CSS.

###  Libraries and external resources

| Library | Why we chose it |
|---|---|
| **[Google Fonts](https://fonts.google.com/)** | To load Plus Jakarta Sans and Caveat quickly and for free. |
| **[Remix Icon](https://remixicon.com/)** | Clean, modern icons that match the style of the site (cards, arrows, alerts). |
| **[Font Awesome](https://fontawesome.com/)** | Social media icons for the footer. |
| **[Cloudinary](https://cloudinary.com/)** | To host images in the cloud and keep heavy files out of the repository. |

---

##  Project architecture

```
Ultreia/
├── index.html      → Home page
├── contact.html    → Contact and help page
├── styles.css      → Stylesheet shared by all pages
└── README.md       → Project documentation
```

### Home page sections

| Section | Description |
|---|---|
| **Nav** | Logo, navigation menu and action buttons |
| **Hero** | Main image with the motto *"We walk the Camino together"* |
| **Pilgrim's greeting** | Explains the origin of the name Ultreia |
| **What do you need?** | Four quick links: I need help, I want to help, I want to offer and I don't walk alone |
| **Impact areas** | Eight cards that flip on hover with information about each area |
| **Community board and map** | Latest community posts and a resource map |
| **Incidents** | Call to action to report problems on the Camino |
| **Footer** | Navigation, impact areas, legal information and credits |

### Contact page

| Section | Description |
|---|---|
| **Header** | *"We're with you on the Camino"* |
| **Emergency numbers** | 112, 062, 091 and 061 |
| **Ultreia chat** | Expandable FAQs built with `<details>` and `<summary>` |
| **Other ways to contact us** | Phone, email and opening hours |

---

##  Good practices

- **Semantic HTML**: use of `<header>`, `<section>`, `<footer>`, `<details>`...
- **Accessibility**: alternative text (`alt`) on images and `aria-label` on social media icons.
- **camelCase naming** for all classes (`navMenu`, `heroTitle`...).
- **CSS organised by sections**, with comments marking each block.
- **Responsive design** with *Flexbox*, *CSS Grid* and *media queries* for mobile, tablet and desktop.
- **Pure CSS animations**: `@keyframes`, `transition` and `transform`.
- **Branches and commits in English**, with clear messages describing each change.
- **Optimised images** hosted on Cloudinary.

---

##  Installation and usage

This project **doesn't require installing any dependencies** or a `.env` file, since it is a static website built with HTML and CSS.

### 1. Clone the repository

```bash
git clone https://github.com/Daniel-Chaves-Dominguez/Ultreia.git
cd Ultreia
```

### 2. Open the project

**Option A · With Visual Studio Code and Live Server (recommended)**

1. Open the project folder in **VS Code**.
2. Install the **Live Server** extension.
3. Right-click `index.html` → **Open with Live Server**.

**Option B · Directly in the browser**

Double-click `index.html`.

>  An internet connection is required to load the fonts, icons and images, which are served from Google Fonts, Remix Icon, Font Awesome and Cloudinary.

---

##  Version control

We worked with **Git and GitHub**, using **one branch per section** of the website. Once a section was finished, it was merged into `main`.

| Branch | Section | Owner |
|---|---|---|
| `navbar` | Navigation | Alba |
| `hero` | Hero | Alba |
| `pilgrimGreeting` | Pilgrim's greeting | Daniel |
| `whatDoYouNeed` | What do you need? | Daniel |
| `cards` | Impact areas | Melissa |
| `community-board` | Community board and map | Alba |
| `incident` | Incidents | Daniel |
| `footer` | Footer | Melissa |

**Workflow we followed:**

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
git checkout -b branch-name
# ...changes...
git add .
git commit -m "Add navbar with logo, menu and buttons"
git push -u origin branch-name
```

###  Improvement identified

We created each section's branch **directly from `main`**. The correct approach would have been to use an intermediate **`dev`** (development) branch, so that `main` only receives stable, reviewed versions:

```
main  ← stable versions only
 └── dev  ← sections are integrated and tested here
      ├── navbar
      ├── hero
      ├── ...
      └── footer
```

This way, if something breaks when merging a section, the error stays in `dev` and the published site on `main` (and on Vercel) keeps working. We will apply this in future projects.

---

##  Methodology

We followed an **agile methodology inspired by Scrum**:

- **Trello** to organise tasks into columns (*To do*, *In progress*, *Done*).
- **Tasks split by section**, so each team member could work in parallel without overwriting each other's work.
- **Team reviews** before merging each branch into `main`.

 **[View the Trello board](https://trello.com/b/A9NZHmCw/ultreia)**

---

##  What we learned

- Working as a team with **Git and GitHub using branches**, and resolving conflicts.
- The importance of having a **`dev`** branch between `main` and the working branches to protect the published version.
- Turning a **Figma design into code** while respecting colours, typography and spacing.
- Building **interactions and animations with CSS only**, without JavaScript.
- Creating layouts with **Flexbox and Grid** and adapting the site to different screen sizes.
- Organising code with a **shared naming convention** (camelCase) so the whole team can understand it.
- **Deploying** a website on Vercel.

---

##  Next steps

- [ ] Work with the **`main` → `dev` → feature branches** workflow.
- [ ] Add **JavaScript** to make the map filters and the chat interactive.
- [ ] Connect the forms to a **back-end** to store requests and incident reports.
- [ ] Integrate a real **interactive map** showing the location of resources.
- [ ] Build a **user system** so people can post on the community board.
- [ ] Translate the site into other languages (**English, Galician, Portuguese**) for pilgrims from all over the world.
- [ ] Improve **accessibility** with contrast checks and keyboard navigation.

---

##  Team

| | Name | Profile |
|---|---|---|
|  | **Alba Ruiz de la Vega** | [LinkedIn](https://www.linkedin.com/in/alba-ruiz-de-la-vega-765b21384/) |
|  | **Daniel Chaves Domínguez** | [GitHub](https://github.com/Daniel-Chaves-Dominguez) |
|  | **Melissa Guerrero** | [LinkedIn](https://www.linkedin.com/in/melissafguerreroc/) |

---

<div align="center">

**Ultreia et suseia!** 

© 2026 Ultreia. All rights reserved.

</div>
