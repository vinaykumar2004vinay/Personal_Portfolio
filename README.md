# Vinay Kumar — Portfolio Website

Hi, I'm **Dasari Vinay Kumar**, a Java Full Stack Developer from Tirupati, Andhra Pradesh. This is the source code of my personal portfolio website, where I share who I am, what I know, and the projects I've built.

I built it with React and Vite, and it works nicely on both desktop and mobile.

## What's on the site

- **Home** – a quick intro, my photo, and buttons to view projects or download my resume
- **About** – what I do across full stack development, secure APIs, and databases
- **Skills** – the tools and technologies I work with
- **Projects** – the applications I've built, with what they do and the tech behind them
- **Experience & Education** – my internship, degree, and certification
- **Contact** – email, GitHub, and LinkedIn links

## Projects featured

1. **Online Food Delivery Platform** – customers can browse restaurants, search dishes, manage a cart, and place orders. Restaurant owners get a dashboard for menus and orders, and payments run through Razorpay.
2. **Multi-Vendor E-Commerce Platform** (internship project at SystemTron) – separate experiences for customers, sellers, and admins, with JWT login, Razorpay and Stripe payments, and an AI product assistant powered by Gemini.

## Built with

- React
- Vite
- lucide-react (icons)
- Plain CSS for styling and responsive layout

## Run it on your computer

You'll need [Node.js](https://nodejs.org/) (LTS version) installed.

```bash
# 1. Clone the repo
git clone https://github.com/vinaykumar2004vinay/<repo-name>.git
cd <repo-name>

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
```

Then open the address Vite shows you, usually `http://localhost:5173`.

To make a production build:

```bash
npm run build
npm run preview   # optional: preview the build locally
```

## Project structure

```
vinay-portfolio/
├── public/
│   ├── profile.jpg     # my profile photo
│   └── resume.pdf      # my resume (the download button uses this)
├── src/
│   ├── App.jsx         # all the content and sections
│   ├── index.css       # design and responsive styles
│   └── main.jsx        # app entry point
├── index.html
└── package.json
```
