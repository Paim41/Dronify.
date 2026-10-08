<div align="center">

<img src="assets/dronifylogo2.png" width="140" alt="Dronify Logo" />

# Dronify

*A clean, responsive drone catalogue for discovering camera, FPV racing, and agricultural drones — built with HTML and CSS.*

<img src="https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Semantic" />
<img src="https://img.shields.io/badge/CSS3-Responsive-2563A6?style=for-the-badge&logo=css&logoColor=white" alt="CSS3 Responsive" />
<img src="https://img.shields.io/badge/Catalogue-6%20Drones-182E47?style=for-the-badge" alt="6 Drones" />
<img src="https://img.shields.io/badge/Website-Static-F1F7FC?style=for-the-badge&labelColor=2563A6&color=F1F7FC" alt="Static Website" />

</div>

---

## What works locally

- **Home page** — drone-themed introduction with a featured hero image
- **Drone catalogue** — browse six drone models across three categories
- **Category navigation** — jump directly to Camera, FPV Racing, or Agricultural Drones
- **Featured drones** — quick access to selected models from the home page
- **Individual product pages** — dedicated details for all six drones
- **Product specifications** — product codes, brands, uses, listed prices, and example stock information
- **Related products** — navigate to another drone in the same category
- **Responsive UI** — layouts that adapt to desktop, tablet, and mobile screens
- **Accessible navigation** — semantic page structure, skip links, and visible keyboard focus
- **Subtle interactions** — hover effects, smooth scrolling, and reduced-motion support
- **Local assets** — logo and drone images are included with the project

*Dronify is an educational drone catalogue, not a live e-commerce store. Listed prices, availability, and stock quantities are examples and are not verified in real time.*

---

## Drone collection

| Category | Product code | Drone model |
|---|---|---|
| Camera Drones | `CAM-101` | DJI Mini 5 Pro |
| Camera Drones | `CAM-102` | DJI Lito 1 Fly |
| FPV Racing Drones | `FPV-201` | GEPRC MOZ7 V2 |
| FPV Racing Drones | `FPV-202` | GEPRC MARK5 |
| Agricultural Drones | `AGR-301` | DJI Agras T25 Agriculture Drone |
| Agricultural Drones | `AGR-302` | S50 Agriculture Spreading Drone (ABZ Innovations) |

---

## Requirements

| Requirement | Detail |
|---|---|
| Web browser | A modern desktop or mobile browser |
| HTML | HTML5 |
| CSS | CSS3 |
| JavaScript | Not required |
| Node.js / npm | Not required |
| Database | Not required |

*No packages, environment variables, API keys, or external service credentials are needed to run the website.*

---

## Local setup

1. Download or clone the Dronify repository.
2. Open the project folder.
3. Open **`index.html`** in your web browser.
4. Select **Catalogue** to browse all six drones.

Alternatively, serve the project from its root directory with Python:

```bash
python -m http.server 8000
```

Then visit **http://localhost:8000**.

### Main pages

| Page | File | Purpose |
|---|---|---|
| Home | `index.html` | Introduction, categories, and featured drones |
| Catalogue | `catalogue.html` | All drone models grouped by category |
| Product details | `products/*.html` | Specifications and related-drone links |

*Because Dronify is a static HTML/CSS website, no build command is required.*

---

## Design system

Dronify uses a **blue, navy, and white** visual identity with clean spacing, simple cards, and responsive layouts.

| Design token | Color | Usage |
|---|---|---|
| Primary blue | `#2563A6` | Buttons, links, and accents |
| Dark blue | `#194B83` | Hover states |
| Navy | `#182E47` | Headings and branding |
| Ice blue | `#F1F7FC` | Soft section backgrounds |
| White | `#FFFFFF` | Main page background |
| Body text | `#34475C` | Main reading text |

*The interface uses Arial/Helvetica system fonts and includes a reduced-motion fallback.*

---

## Project structure

```text
Dronify/
├── index.html                  Home page
├── catalogue.html              Complete drone catalogue
├── products/
│   ├── cam-101.html            DJI Mini 5 Pro
│   ├── cam-102.html            DJI Lito 1 Fly
│   ├── fpv-201.html            GEPRC MOZ7 V2
│   ├── fpv-202.html            GEPRC MARK5
│   ├── agr-301.html            DJI Agras T25
│   └── agr-302.html            ABZ Innovations S50
├── css/
│   ├── style.css               Main stylesheet
│   └── stylecomment.css        Additional commented stylesheet
├── assets/
│   ├── dronifylogo.png         Logo asset
│   ├── dronifylogo2.png        Logo used in the website header
│   ├── dronehome.png           Home hero image
│   ├── cam-101.png
│   ├── cam-102.png
│   ├── fpv-201.png
│   ├── fpv-202.png
│   ├── agr-301.png
│   └── agr-302.png
└── README.md
```

---

## Project notes

| Item | Detail |
|---|---|
| Project | Dronify |
| Coursework | BIC21203 — Lab 03 |
| Website type | Educational drone product catalogue |
| Architecture | Static multi-page website |
| Categories | 3 |
| Drone models | 6 |
| Payments / checkout | Not implemented |
| Live inventory | Not connected |
| Backend / database | Not used |

*Product information and imagery are included for educational presentation. Product photos may be replaced and sample information should not be treated as current retailer data.*

---

<div align="center">

**Dronify — Explore the world of drones.**

*Discover the technology. Explore the possibilities.*

</div>
