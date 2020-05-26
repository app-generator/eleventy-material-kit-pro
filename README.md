# [Eleventy Material Kit PRO](https://appseed.us/static-site/eleventy-material-kit-pro)

> Commercial product - [Eleventy](https://www.11ty.io/) SSG starter with **Material Kit PRO Design** - Features:

- UI Kit: **Material Kit PRO** provided by **Creative-Tim**
- SSG [11ty](https://www.11ty.io/)
- [Sass/SCSS](https://github.com/sass/node-sass)
- [Webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)
- [light-server](https://github.com/txchen/light-server)
- [PostCSS](https://postcss.org/)
- [CSSnano](https://cssnano.co/)
- [Autoprefixer](https://github.com/postcss/autoprefixer)
- **Commercial License**
- 24/7 Live Support via [Discord](https://discord.gg/fZC6hup).

> Links

- [Eleventy Material Kit PRO](https://eleventy-material-kit-pro.appseed.us/) - LIVE Demo
- [Eleventy Material Kit PRO](https://appseed.us/static-site/eleventy-material-kit-pro) - Official product page
- [Material Kit PRO](https://demos.creative-tim.com/marketplace/material-kit-pro/docs/2.0/getting-started/introduction.html) - Official UI Docs

<br />

![Eleventy Material Kit PRO - Eleventy SSH starter with Material PRO Design.](https://raw.githubusercontent.com/app-generator/eleventy-material-kit-pro/master/media/eleventy-material-kit-pro-screen.png)

<br />

## Project Structure

The boilerplate code is built with a modular structure that follows the recommended pattern used by many open-source projects. The most important files and  directories are shown below:

<br />

```bash
< PROJECT ROOT >
   |
   |-- src/                              # App Sources
   |    |
   |    |-- assets/                      # Static assets folder
   |    |    |-- <css, JS, images>       # CSS files, Javascripts files
   |    |
   |    |-- _data_/
   |    |     |-- data.json              # Store global variables
   |    |
   |    |-- _includes/
   |          |-- layouts/               # The master-pages directory
   |               |
   |               |-- base.njk          # Master layout used by common pages
   |               |-- base-auth.njk     # Master layout used by authentication pages
   |               |-- base-contact.njk  # Master layout used by contact form
   |               |
   |           footer.njk                # Footer component
   |           header.njk                # Header component
   |           navigation.njk            # Top Menu
   |           scripts.njk               # Common JS scripts
   |
   |-- .eleventy.js                      # Used to configure 11ty
   |-- package.json                      # Node script manager
   |-- deploy.js                         # FTP upload script
   |
   |-- ************************************************************************
```

<br />

## How to use it

- Build from sources:

```bash
$ # Get the code
$ git clone https://github.com/app-generator/priv-eleventy-material-kit-pro.git
$ cd priv-eleventy-material-kit-pro
$ 
$ # Install modules
$ yarn
$ 
$ # Start in development mode
$ yarn start
$ 
$ # app is running on http://localhost:4000
$ 
$ # Production build
$ yarn build
```

> Please visit the static site in your preferred browser. For production build type `yarn build`:

```bash
$ # Production build
$ yarn build # the static site is generated in dist/ folder
$ 
$ # Visualize the HTML files using PHP:
$ cd dist
$ php -S localhost:4000
```

> Please visit `localhost:4000` in the browser to visualize the production build.

<br />

## What is [Eleventy](https://www.11ty.dev/)

Eleventy (11ty) is a simpler SSG created to be a JavaScript alternative to Jekyll. It’s zero-config by default but has flexible configuration options. Eleventy works with your project’s existing directory structure.

Eleventy uses independent template engines. We don’t want to hold your content hostage. If you decide to use something else later, having your content decoupled in this way will make migration easier.

Eleventy works with multiple template languages. You can pick one or use them all together in a single project: HTML, Markdown, Javascript, Nunjunks.

<br />

## [Material Kit PRO](https://www.creative-tim.com/product/material-kit-pro/?ref=appseed)

Material Kit PRO, a UI KIT inspired by Google's Material Design, features over 1000 individual components, giving you the freedom of choosing and combining. This means that there are thousands of possible combinations. All components can take variations in colour that you can easily modify using SASS files.

Material Kit comes packed with a large number of sections. Putting together a page has never been easier than matching together sections. From team presentation to pricing options, you can easily customise and built your pages. We have created multiple options for you to put together and customise into pixel perfect pages.

<br />

---
[Eleventy Material Kit Pro](https://appseed.us/static-site/eleventy-material-kit-pro) - Provided by **AppSeed** [Web App Generator](https://appseed.us/app-generator).
