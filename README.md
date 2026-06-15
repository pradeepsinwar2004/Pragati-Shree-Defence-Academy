# 🔗 Pragati Shree Defence Academy
### Responsive academy landing page — HTML + CSS + JavaScript

Pragati Shree Defence Academy is a static promotional website for the academy. It presents the academy brand, navigation, admissions and facilities sections, selected candidate highlights, and social links in a simple single-page layout.

---

# 📌 Problem Statement

Prospective students and parents need a clean way to learn about the academy, its facilities, admissions, and success stories. This project solves that by providing:
- A simple, mobile-friendly homepage
- Easy access to facilities, admissions, and about sections
- A visual showcase of selected candidates
- Lightweight interactivity without any backend dependency

---

# 🚀 Key Features

## 🧭 Navigation Menu

- Top navigation with dropdown menus for Facilities, Admissions, and About Us
- Simple click-to-open dropdown behavior powered by JavaScript
- Click outside to close open menus

## 🏫 Academy Hero Section

- Branded header with academy identity and banner imagery
- Central message focused on motivation and discipline
- Clean hero-style presentation for the landing page

## 🎓 Selected Candidates Showcase

- Highlight cards for selected candidates from different locations
- Candidate names, places, and short testimonial quotes
- Grid-based layout for visual presentation of results

## 📱 Social Footer

- Footer links for Facebook, Instagram, and X/Twitter
- Compact contact strip for quick brand visibility

## ⚙ Minimal Frontend Patterns

- Built with plain HTML, CSS, and JavaScript
- No framework or build step required
- Easy to edit and deploy as a static site

---

# 🧠 How It Works

1. The browser loads `index.html` and applies the styles from `style.css`.
2. The header, navigation, motivational hero, candidate cards, and footer are rendered in one page.
3. `main.js` toggles the dropdown menus for Facilities, Admissions, and About Us.
4. If the user clicks anywhere outside the buttons, the dropdowns close automatically.

---

# 🏗 System Architecture

```txt
User Browser
	└─ Opens index.html
			 │
			 ├─ style.css  → page layout, colors, grid/flex styling
			 ├─ main.js    → dropdown interactions
			 └─ images     → logo, banner, candidate photos, icons
```

---

# 🛠 Tech Stack

## Frontend

- HTML5
- CSS3
- JavaScript

## Assets

- Local image files for branding and candidate cards
- SVG icons for social links and dropdown indicators

---

# 📂 Project Structure

```txt
Pragati-Shree-Defence-Academy/
├── index.html          # Main landing page
├── style.css           # Page styling and layout
├── main.js             # Dropdown menu interactions
├── README.md           # Project documentation
└── assets/images       # Local images and icons used by the page
```

See [index.html](index.html) for the page structure, [style.css](style.css) for the visual design, and [main.js](main.js) for the dropdown behavior.

---

# 📡 Page Sections

## Header

- Academy branding and banner presentation
- Logo and profile-style image placement

## Navigation

- Home link
- Facilities dropdown
- Admissions dropdown
- About Us dropdown

## Main Highlight

- “Towards The Success” motivational section
- Academy-oriented mission statement

## Selected Candidates

- Four grid rows of candidate result cards
- Image, name, location, and testimonial text for each card

## Footer

- Social handles and contact-style links

---

# ⚙ Installation

## 1. Clone repository

```bash
git clone <repo-url>
cd Pragati-Shree-Defence-Academy
```

## 2. Open the project

Open `index.html` directly in your browser, or use a local static server if preferred.

## 3. Serve locally, optional

If you want a local server, use any static file server you like. For example:

```bash
npx serve .
```

## 4. Edit content

Update `index.html`, `style.css`, and `main.js` to change text, layout, images, or dropdown behavior.

---

# 🧪 Example Usage

Open the homepage in a browser and interact with the navigation:

- Click `Facilities` to open the facilities dropdown
- Click `Admissions` to view batch options
- Click `About Us` to see academy information links
- Scroll through the selected candidate showcase and footer links

---

# 📈 Future Improvements

* Add responsive mobile navigation
* Replace placeholder links with real destination pages
* Add admissions forms and contact details
* Create separate pages for faculties, hostel, mess, and medical facilities
* Add a testimonial slider or gallery section
* Improve accessibility with better alt text and keyboard support

---

# 💡 Engineering Highlights

* Pure static implementation with no framework overhead
* Simple dropdown interactions in a small JavaScript file
* Grid and flex layout used for structured page sections
* Easy to deploy to any static hosting platform

---

# ⚠ Important Notes

* Several navigation links are currently placeholders and should be connected to real pages or routes.
* Some images are loaded from local files, so they must remain in the project folder for the page to render correctly.
* The project is best treated as a landing page or brochure site rather than a full web application.

---

# 🤝 Contributing

Contributions welcome — open issues or pull requests for:

- Responsive layout improvements
- Content updates and new sections
- Accessibility fixes
- Real link routing and page expansion

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Pradeep Kumar Sinwar

Backend Developer | Competitive Programmer

---

# 🏁 Final Goal

Provide a clean, informative academy website that presents the brand, highlights success stories, and makes core information easy to find.
