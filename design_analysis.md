# Design Analysis and Page Identification

Based on the provided screenshots, the following pages and common design elements have been identified for the HTML/CSS template project.

## Common Elements
All pages share a consistent header and footer, suggesting a single, shared CSS file for these components.

### Header/Navigation Bar
- **Branding:** "EVENTIFY" logo/text on the left.
- **Navigation Links (in French):** HOME, DEMANDE DISPONIBLE, MES DEMANDES, EVALUATION, JEUX, PORTEFEUILLE.
- **Search Icon:** A search icon on the far right.
- **Color Scheme:** Dark brown/gold background for the navigation bar.

### Footer
- **Branding:** "EVENTIFY" logo/text.
- **Contact Information:** Email (`help@eventify.tn`), Contact number (`92 225 335`).
- **Social Media:** LinkedIn icon and link (`Linkedin eventify.tn`).
- **Color Scheme:** Dark brown/black background.

## Identified Pages

| Screenshot File | Page Name (Proposed HTML File) | Description | Key Components |
| :--- | :--- | :--- | :--- |
| `ONE.png` | `mes_missions.html` | **MES MISSIONS** (My Missions) - A list view of user's missions/tasks. | Search bar, filter/sort by "PRIX", list of missions with title, date, description, status (en cours/en Attent), and action icons (view, cancel). |
| `SEVEN.png` | `demandes_disponibles.html` | **DEMANDES DISPONIBLE** (Available Requests) - Similar list view, likely for requests the user can take on. | Search bar, list of available requests with title, date, description, status (en cours/en Attent), and action icons (view, cancel, accept). |
| `SIX.png` | `historique_demande.html` | **HISTORIQUE DE DEMANDE** (Request History) - A simpler list view of past requests. | Search bar, list of past requests with title, date, description, and status. |
| `TWO.png` | `demande_detaillee.html` | **DEMANDE DETAILLÉ** (Detailed Request) - A detailed view of a single request. | Left panel with a large image/graphic ("MyUniLife"), right panel with form-like fields (Titre, Description, Récompense, Adresse, Contact, Durée), and action buttons (Retour, Accepter). |
| `THREE.png` | `evaluation.html` | **EVALUATION** (Evaluation/Reviews) - A page displaying overall ratings and individual reviews. | Summary statistics (Total Avis, Note Moyenne), star rating distribution chart, and a list of individual user reviews with profile picture, name, date, and comment. |
| `FOUR.png` | `jeux.html` | **JEUX** (Games) - A page featuring a "Spin the Wheel" game. | A large interactive wheel graphic, "Spin" button, "Spin restant" counter, and a "HISTORIQUE DE GAGNE" (Win History) panel. |
| `EIGHTT.png` | `portefeuille.html` | **MON PORTEFEUILLE** (My Wallet) - A dashboard for financial transactions. | Summary cards (Solde Actuel, Transaction en Attent, Transaction Valider), and a list of "TRANSACTIONS À VALIDER" (Transactions to Validate) with user profiles and a "Valider" button. |

## Design Notes
- **Color Palette:** Dominated by a light beige/off-white background, with dark brown/gold accents for headers and key elements. Green is used for success/validation.
- **Typography:** Clean, modern sans-serif font.
- **Layout:** Generally a centered, fixed-width layout with a main content area.
- **Icons:** Requires icons for search, wallet, clock, checkmark, eye, cross, and social media (LinkedIn, envelope, phone). Font Awesome or similar icon library will be used.
- **Images:** Placeholder images will be used for user profiles and main content graphics.

## Project Structure (Proposed)

```
web_project/
├── index.html (Redirect or simple home page)
├── css/
│   └── style.css (Shared styles for header, footer, layout, and common components)
├── pages/
│   ├── mes_missions.html
│   ├── demandes_disponibles.html
│   ├── historique_demande.html
│   ├── demande_detaillee.html
│   ├── evaluation.html
│   ├── jeux.html
│   └── portefeuille.html
└── assets/
    ├── images/ (Placeholder images)
    └── fonts/ (Optional, if custom font is needed)
```
