# Prime Point Learnings

Prime Point Learnings is a personal coaching website for triathlon athletes. It presents training plans, athlete results, and a contact form so visitors can request a personalized plan.

The interface is a single-page home with a separate contact route, built with React and Tailwind CSS.

## Features

- Home page with a hero, performance stats, coaching plans, testimonials, an about section, and an FAQ
- Three coaching plans: Basic, Standard, and Premium
- Animated about section and testimonial carousel
- Contact page with phone, email, and an inquiry form
- Mobile navigation and hash-link scrolling to page sections
- Call-to-action banner that links back to the contact page

## Tech stack

- React 19
- Vite 7
- React Router DOM
- React Router Hash Link
- Tailwind CSS 4
- Framer Motion
- React Icons
- React CountUp

## Getting started

Requirements: Node.js 18 or newer.

```bash
npm install
npm run dev
```

Then open the local URL Vite prints, usually `http://localhost:5173`.

## Scripts

| Command | Purpose |
| --- | --- |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build in `dist` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Routes

| Path | What it shows |
| --- | --- |
| `/` | Home: hero, features, coaching plans, testimonials, about, FAQ, and footer |
| `/contact` | Contact form, testimonials, call to action, and footer |

## Project structure

```text
src/
  main.jsx                 App entry
  MainRouter.jsx           Routes for home and contact
  App.jsx                  Home page sections
  Components/
    Navbar.jsx             Desktop and mobile navigation
    Hero.jsx               Opening section and start button
    Features.jsx           Coaching overview and stats
    Coaching.jsx           Basic, Standard, and Premium plans
    Testomonail.jsx        Client testimonials
    About.jsx              Coach story
    FAQ.jsx                Common questions
    Contact.jsx            Phone, email, and inquiry form
    Ready.tsx              Closing call to action
    Footer.jsx             Links and socials
```

## Contact

- Phone: +91 98450 21736
- Email: hello@primepointlearnings.com
