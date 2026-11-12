# Aura Glow Parlour — Portfolio Demo

A polished, responsive landing-page concept for a fictional beauty parlour and spa in Nairobi. This project is designed as a portfolio demonstration for prospective clients; all names, testimonials, prices, locations, and contact details are sample content.

## Live experience

The single-page site guides visitors through the brand story, featured services, sample testimonials, and a conversion-focused booking section. The page includes a visible demo notice so it cannot be mistaken for a real operating business.

## Features

- Responsive, mobile-first layout
- Accessible semantic HTML and keyboard focus states
- Service cards and testimonial carousel
- Conversion-focused booking section
- Clear portfolio/demo disclosure
- Lightweight static build with no required installation

## Built with

- HTML5
- CSS3
- Bootstrap 5.3
- Bootstrap Icons
- Google Fonts
- Node.js development server (no packages required)

## Run locally

Clone the repository, open a terminal in the project folder, and start the included dependency-free static server:

```bash
npm start
```

Then visit `http://localhost:5500` in a browser. You can also open `index.html` directly or use the VS Code Live Server extension.

> Run `nodemon server.js` if you prefer automatic server restarts. Do not run `nodemon index.html`; Node cannot execute an HTML document.

## Publish with GitHub Pages

1. Create a new empty repository on GitHub.
2. Add it as the remote for this local repository:

   ```bash
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git branch -M main
   git push -u origin main
   ```

3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.

## Customize for a real client

Replace the fictional brand name, sample reviews, service prices, contact actions, location, and image URLs with verified client content before publishing as a production business website.

## Project status

Portfolio demonstration — not a live business website.
