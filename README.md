<p align="center">  
    <img width="400" height="140" src="https://svgshare.com/i/Qo0.svg">
</p>


# Livestorm Lead Developer (Website) Test


Be sure to read all of the instructions carefully and follow the guidelines below. This test should take you between 4 and 8 hours depending on your experience.

As a Lead Front-End Developer for the website, you'll be tasked with every aspect of the website's infrastructure: from improving its performance (deploy times, Google lighthouse score...) to integrating new components and pages while being pixel perfect, adding animations, and overall choosing the best libraries, plugins and solutions for each project we'll have.

This test will give a framework for evaluating your skills in those areas.

# Context


You are tasked with setting up a simple static site using the same stack as Livestorm (defined below).

You will integrate 2 layouts, and 3 pages in total:

- A single page which is an index for the use cases single pages
- 2 single pages, accessible from the index

The structure will look like:

Index: `testurl.netlify.app/use-cases/`

Page: `testurl.netlify.app/use-cases/page-slug/`

# Design


All screens are available in the [Figma source file](https://www.figma.com/file/O6eFbbxDL3OJaGpqAAjgq2/Website---Iterations-NEW-(Copy)?node-id=3%3A2).

All the assets are in the Figma file as well.

The behavior of the animation you'll need to recreate is [in this video.](https://livestorm.wistia.com/medias/4b6c580rvq)

Important: If you haven't already, sign up for a free Figma account and sign in, so you can inspect the design.

# Tech requirements


A few technologies / libraries used for the static site, must be used:

- Vue.js 2
- Nuxt.js CLI (as a static site)
- [Tailwind CSS](https://tailwindcss.com/)
- DatoCMS
- GraphQL
- Netlify

# What you need to do


- Create the Nuxt CLI project from scratch, enabling full static mode
- Write the logic for the pages' build and deploy as a static site to Netlify
- Being as close as possible to the Figma files design, including the animation
- Make it possible to edit the site's content via DatoCMS, with all these requirements:
    - Enable Draft/Published records
    - Allow to modify all content within DatoCMS
    - Allow to deploy from DatoCMS (according to the Draft/Published status)

# How to send your site's code


When you feel you are done, send us by email:

- A link to a **private GitHub repository** with an invite access for [@VincentGarreau](https://github.com/VincentGarreau) & [@ThibautDavoult](https://github.com/ThibautDavoult)
- An **online demo** of the website (on the free version of Netlify)
- Share **the access to the DatoCMS project** (with an easily shareable, temporary passord)

# Tips


- Being as close as possible to the Figma screens is very important
- The site must be responsive! It should look good and work on both mobile and desktop screens!
- You shouldn't have to customize Tailwind, the default configuration is enough to be able to match the Figma screens
- Feel free to use Google Fonts to import Inter font
- Show off your Vue and GraphQL skills! Don't hesitate to use more advanced Vue, vue-router or Apollo client features and good practices
- (Bonus) Write clear README on how the app was designed and how to run the code
- (Bonus) Describe optimization opportunities
- Got questions? Contact us! (No penalties for asking questions 😉️)
