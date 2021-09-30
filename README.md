<<<<<<< HEAD
<p align="center">
  <a href="https://cara.lekoarts.de">
    <img alt="LekoArts" src="https://img.lekoarts.de/gatsby/gatsby-site-illustration.png" />
  </a>
</p>
<h1 align="center">
  My Developer Portfolio Website ⚡️
</h1>

<!--<p align="center">
   <a href="https://github.com/LekoArts/gatsby-starter-portfolio-cara/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-0BSD-blue.svg" alt="Gatsby Starter Portfolio: Cara is released under the 0BSD license." />
  </a>
  <a href="https://github.com/sponsors/LekoArts">
    <img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/LekoArts">
  </a>
  <a href="https://www.lekoarts.de?utm_source=cara&utm_medium=Starter">
    <img alt="Website" src="https://img.shields.io/badge/-website-blue">
  </a> 
</p>-->
<h2>
Welcome! 
</h2>
<p>
My portfolio site was built from a Gatsby template. Playful and Colorful One-Page portfolio featuring Parallax effects and animations. Using the Gatsby Theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara). I took notes on how a more experienced dev sets up front-end data flow for a static site. It was also my first time working with Gatsby, SaSS, and GraphQL.
</p>
<h2>
What I Changed
</h2>
<ul>
  <li>
    Added external Link buttons to the top and bottom of the site
  </li>
  <li> 
    Added Nav buttons to quickly get to your desired section
  </li>
  <li>
    Added a new section for skills and changed section order (this messed with the original formatting quite a bit) 
  </li>
  <li>
    Built a Contact Form and integrated email notifications through Netlify 
  </li>
  <li>
    Swapped project images for iframes with project demo videos on YouTube 
  </li>
  <li>
    Skills feature: I built a component that renders a different image of a burger depending on where on the burger the cursor hovers or clicks. The burger images were created in photoshop. I built one div with the burger nested inside, that has a sibling div (position: absolute, same height and width as the img) with 3 child divs each taking up about one third of that div's height. Those three divs had event listeners that triggered state change in React, which rendered a new burger img and skills set. Each skills set had to be a different component to trigger the animation. My favorite part of the site. 😊 🍔 
  </li>
  <h2>
    What I Learned 
  </h2>
  <ul>
    <li>
      Created CSS Variables in SaSS 
    </li>
    <li>
      Learned how to use clip-path in CSS 
    </li>
    <li>
      Gatsby project structure 
    </li>
    <li>
      Deployed a site to Netlify 
    </li>
    <li>
      Burger 
    </li>
    <h2>
      Thanks 
    </h2>
      <p>
        Thanks to LekoArts - https://github.com/LekoArts/gatsby-starter-portfolio-cara for designing this fantastic template.
      </p>
      <p>
        Here's what the template looked like before, if you're curious:



Also be sure to check out other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de) and my [Personal Website](https://www.lekoarts.de?utm_source=cara&utm_medium=Starter).

## ✨ Features

- Theme UI-based theming
- react-spring parallax effect
- CSS Animations on Shapes

## 🚀 Getting Started

[<img src="https://www.gatsbyjs.com/deploynow.svg" alt="Deploy to Gatsby Cloud">](https://www.gatsbyjs.com/dashboard/deploynow?url=https://github.com/LekoArts/gatsby-starter-portfolio-cara)

### 1. **Create a Gatsby site.**

Use `git` to clone the site and navigate into it:

```sh
git clone https://github.com/LekoArts/gatsby-starter-portfolio-cara project-name
cd project-name
```

### 2. **Install dependencies.**

If you use npm 7 or above use the `--legacy-peer-deps` flag. If you use npm 6 you can use `npm install`.

```sh
npm install --legacy-peer-deps
```

### 3. **Open the code and start customizing!**

Start the site by running `npm run develop`.

Your site is now running at `http://localhost:8000`!

If you want to learn more about how you can use a Gatsby starter that is configured with a Gatsby theme, you can check out this [shorter](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/using-a-gatsby-theme/) or [longer](https://www.gatsbyjs.com/tutorial/using-a-theme/) tutorial. The tutorials don't exactly apply to this starter however the concepts are the same.

## 📝 Using and modifying this starter

**Important Note:** Please read the guide [Shadowing in Gatsby Themes](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/shadowing/) to understand how to customize the underlying theme!

This starter creates a new Gatsby site that installs and configures the theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).

Have a look at the theme's README and files to see what options are available and how you can shadow the various components including Theme UI. Generally speaking you will want to place your files into `src/@lekoarts/gatsby-theme-cara/` to shadow/override files. The Theme UI config can be configured by shadowing its files in `src/gatsby-plugin-theme-ui/`.

### Changing content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. This starter has overridden the `intro.mdx` file as an example. Place the other files in the same `src/@lekoarts/gatsby-theme-cara/sections/` folder.

You have to use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md
## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
```

### Change your `static` folder

The `static` folder contains the icons, social media images and robots.txt. Don't forget to change these files, too!

## 🤔 Questions or problems?

Please open up an issue on the main repository: [LekoArts/gatsby-themes](https://github.com/LekoArts/gatsby-themes). Thanks!

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on Gatsby's website](https://www.gatsbyjs.com/).

### Themes

- To learn more about Gatsby themes specifically, we recommend checking out the [theme docs](https://www.gatsbyjs.com/docs/themes/).

### General

- **For most developers, I recommend starting with the [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/docs/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to Gatsby's documentation](https://www.gatsbyjs.com/docs/).** In particular, check out the _Reference Guides_ and _Gatsby API_ sections in the sidebar.

## 🌟 Supporting me

Thanks for using this project! I'm always interested in seeing what people do with my projects, so don't hesitate to tag me on [Twitter](https://twitter.com/lekoarts_de) and share the project with me.

Please star this project, share it on Social Media or consider supporting me on [Patreon](https://www.patreon.com/lekoarts) or [GitHub Sponsor](https://github.com/sponsors/LekoArts)!
=======
   ## ✨ My Developer Portfolio Website ⚡️

   Welcome!

My portfolio site was built from a Gatsby template, so I took notes on how a more experienced dev sets up front-end data flow for a static site. It was also my first time working with Gatsby, SaSS, and GraphQL.

## What I Changed

  - Added external Link buttons to the top and bottom of the site
  - Added Nav buttons to quickly get to your desired section
  - Added a new section for skills and changed section order (this messed with the original formatting quite a bit)
  - Built a Contact Form and integrated email notifications through Netlify
  - Swapped project images for iframes with project demo videos on YouTube
  - Skills feature: I built a component that renders a different image of a burger depending on where on the burger the cursor
    hovers or clicks. The burger images were created in photoshop. I built one div with the burger nested inside, that has a
    sibling div (position: absolute, same height and width as the img) with 3 child divs each taking up about one third of that 
    div's height. Those three divs had event listeners that triggered state change in React, which rendered a new burger img
    and skills set. Each skills set had to be a different component to trigger the animation. My favorite part of the site. 😊
    🍔
    
 ## What I Learned
  
    - Created CSS Variables in SaSS
    - Learned how to use clip-path in CSS
    - Gatsby project structure
    - Deployed a site to Netlify

## Thanks

Thanks to LekoArts - https://github.com/LekoArts/gatsby-starter-portfolio-cara for designing this fantastic template. Here's what the template looked like if you're curious:
  <h2 align="center">
   <img src="https://media.giphy.com/media/OorCR8bWKcq0SbFlpZ/giphy.gif?cid=790b7611e43845aac1511b50f83a85683ed917752037a564&rid=giphy.gif&ct=g" alt="Gatsby Starter Portfolio: Cara" width="600px" />
  <br>
</h2>
>>>>>>> f8baff0c5d93c79220f8d1ad8a45e7b597dd1ad8
