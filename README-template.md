# Frontend Mentor - Sunnyside agency landing page solution

Hi everybody! 👋

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef).

## Table of contents  🧾

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge   🎯

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

Mobile Layout 📱

![Mobile Layout](./assets/mobile-layout.jpg)

768px Layout 💻

![Medium Layout](./assets/mediumlayout.jpg)

Desktop Layout 💻

![Desktop Layout](./assets/desktop-layout.jpg)

- See hover states for all interactive elements on the page

![Hover State](./assets/hover-state.gif)

### Links  🔗

- Solution URL: [Github Repository](https://github.com/Arfirpo/sunnyside-agency-landing-page-main)
- Live Site URL: [Github Page](https://arfirpo.github.io/sunnyside-agency-landing-page-main/)

## My process ⚙️

### Built with 🛠️

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Vite](https://es.vitejs.dev/) - Build Tool for React
- [React](https://reactjs.org/) - JS library
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework

### What I learned 📚

This proyect was my first experience whith a build tool (vite) and a framework for javascript (React).
Being my first steps with both technologies, it was a real challenge. Among the things I learned are:
-Creation and management of components
-operation and integration of html elements + jsx code and also its customization with tailwind css.

```jsx
import { Header } from './assets/components/Header'
import { Main } from './assets/components/Main'
import { Service } from './assets/components/Service'
import { TestimonialContainer } from './assets/components/TestimonialContainer'
import { Gallery } from './assets/components/gallery'
import { Footer } from './assets/components/Footer'

function App() {
  return (
    <main className='relative max-w-[90rem] mx-auto'>
      <Header />
      <Main />
      <Service/>
      <TestimonialContainer/>
      <Gallery/>
      <Footer/>
    </main>
  )
}

export default App
```

### Continued development 🔨

My goal from this challenge, is to deepen and master react, leaving, at least for a while, the use of basic technologies (html/css/javascript) to contribute to my growth as a frontend developer

## Author  🙋🏻‍♂️

- Twitter/X - [@agus_firpo](https://twitter.com/agus_firpo)
- Frontend Mentor - [@Arfirpo](https://www.frontendmentor.io/profile/Arfirpo)
- Linkedin - [Agustín Rodrigo Firpo](https://www.linkedin.com/in/agustin-rodrigo-firpo-0aa86697/)