# Chuks Kitchen – Food Ordering Interface

This repository contains a frontend implementation of the Chuks Kitchen Food Ordering System as designed by the UI/UX team at TrueMind Innovations. The goal is to convert the Figma design into responsive, maintainable HTML/CSS pages with Bootstrap, closely mirroring the provided design.

## 🛠 Tech Stack
- **HTML5**
- **CSS3**
- **Bootstrap 5** for layout and responsiveness
- Custom CSS for spacing, typography, and visual details

## 📁 Project Structure
```
Truemind
│
├── index.html       # Landing page
├── home.html        # Main interface page
├── explore.html     # Menu explore page
├── signin.html      # Login page UI
├── signup.html      # Registration page UI
├── assets/
│   ├── images/      # Image assets used across pages
│   └── css/
│       └── style.css# Shared styles (if any)
└── README.md        # This file
```
The structure is intentionally flat to keep navigation simple and support future expansion.

## Design Interpretation
- Layout spacing and typography were implemented according to the Figma spec.
- Buttons include hover and focus styles for visual feedback.
- Uses Bootstrap grid system for two-column hero layouts and responsive product cards.
- Media queries ensure good behavior on tablets and phones.

## Assumptions & Limitations
- **No backend or authentication logic** – all pages are static.
- **Cart and payment functionality** are omitted; only UI components exist.
- Form pages (`signin.html`, `signup.html`) are purely visual.
- Where interactions weren’t defined, sensible defaults were used.

### Future Improvements
- Add JavaScript for interactivity and state (cart, filters, etc.).
- Implement real form validation and API integration.
- Optimize images and assets for performance.

## Learning Outcome
This project emphasized translating UI designs into frontend code while preserving responsiveness and readability. It reinforced how to structure HTML/CSS for clarity and maintainability, preparing the codebase for future enhancements.

## Demo
The site is hosted via GitHub Pages and can be viewed at:

[https://phaith1.github.io/truemind-project1/](https://phaith1.github.io/truemind-project1/)

---

Feel free to clone the repo and explore the pages locally or customize further.