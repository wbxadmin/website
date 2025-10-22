# Vericustos Website

Professional static website for Vericustos Inc. - Post-Quantum Trust Infrastructure

## Structure

docs/ ├── index.html # Homepage ├── pricing.html # Pricing page ├── about.html # About/Team page ├── documentation.html # Technical docs ├── contact.html # Contact form ├── css/ │ └── style.css # Main stylesheet ├── js/ │ └── main.js # JavaScript for interactions ├── images/ # Logo and images └── assets/ # Other assets (PDFs, etc.)


## Deployment
Hosted via GitHub Pages at: https://vericustos.com

## Development
1. Edit files in `/docs` directory
2. Test locally: `python3 -m http.server 8000` from `/docs`
3. Commit and push to deploy

## Tech Stack
- HTML5 + CSS3 (no frameworks for performance)
- Vanilla JavaScript (no jQuery)
- Google reCAPTCHA v3
- Formspree for contact form backend
