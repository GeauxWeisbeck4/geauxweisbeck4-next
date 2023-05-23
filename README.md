![tailwind-nextjs-banner](/public/static/images/twitter-card.png)

# Andrew Weisbeck's Digital Garden

This is Andrew's Digtal Garden, created with the [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), one of the most feature rich and starred blogging starter template's on GitHub/the internet. It features some of the most popular and modern tools that you can easily configure and it is easily customizable to keep it from being too opinionated.

I decided that it would be the perfect template to use to build my digital garden, a content site that features daily updates about my current work and ideas that I share with the internet publicly for my own benefit (feedback) and to help educate everyone else who visits my workspace.

### Here is a to do list currently for me, starting with the original documentation, changed for my purposes

Check out the documentation below to get started.

- [ ] Add sponsorship capabilities to site
- [ ] Add contact form and feature request contact,

If you want to get a hold of me, fill out the appropriate feature request form or fill out my contact form.

## Motivation

I have wanted to make my workspace public in a digital garden since I learned about what such a contraption this wonderful could make when utilized correctly. My own place on the internet where I can create and learn in front of others is really a great concept for breaking down creative barriers that prevent one from concepting successful business ideas, so why not try it out?

Out of all the templates and frameworks I've tried to create this garden in, this starter project that utilizes Next.js and Tailwind CSS is perfect for getting me up and running with the tools I need quickly - no need to start from scratch with such a content rich website. I can make it more to my style and use more creative storytelling tools as time goes on.

- [ ] Add more storytelling features as time goes on and site adapts
- [ ] Add my own SASS CSS as I get more time to work on this
- [ ] Add new blogging features that makes adding content easier
  - [ ] Create a git-based CMS
- [ ] Integrate with tools such as:
  - [ ] Notion
  - [ ] Logseq
  - [ ] Obsidian
  - [ ] Reflect
  - [ ] Linear
  - [ ] GitHub
  - [ ] Jira
  - [ ] GitKraken
- [ ] Integrate with these DBs:
  - [x] MongoDB
  - [ ] PostgreSQL
  - [ ] Supabase
  - [ ] Tigris
  - [ ] Fauna
- [ ] List all Social Media and other websites
- [ ] Make it easy to list on Social Media Websites

## Features

- [ ] Check Lighthouse report score constantly as new code is added
  - Near perfect lighthouse score - [Lighthouse report](https://www.webpagetest.org/result/221104_AiDc59_4WF/)
- [ ] Make sure everything is mobile friendly and responsive
  - Mobile-friendly view
- [ ] Set up light and dark themes in Tailwind Config file
  - Light and dark theme
- [ ] Choose font from Fontsource
  - Self-hosted font with [Fontsource](https://fontsource.org/)
- [ ] Set up analytics tools
  - Supports [plausible](https://plausible.io/), [simple analytics](https://simpleanalytics.com/) and google analytics
- [ ] Set up high light colors and settings with Prism
  - Server-side syntax highlighting with line numbers and line highlighting via [rehype-prism-plus](https://github.com/timlrx/rehype-prism-plus)
- [ ] Setup Rehype settings
  - Citation and bibliography support via [rehype-citation](https://github.com/timlrx/rehype-citation)
- [ ] Make sure all images are optimized
  - Automatic image optimization via [next/image](https://nextjs.org/docs/basic-features/image-optimization)
- [ ] Configure MDX Bundler
  - Flexible data retrieval with [mdx-bundler](https://github.com/kentcdodds/mdx-bundler)
- [ ] Track tags in backend dashboard
  - Support for tags - each unique tag will be its own page
- [ ] Set up authors
  - Support for multiple authors
- [ ] Set up pages
  - Blog templates
- [ ] Set up table of contents
  - TOC component
- [ ] Set up newsletter
  - Newsletter component with support for mailchimp, buttondown, convertkit, klaviyo, revue, and emailoctopus
- [ ] Set up Giscus, Utterances, and Discus
  - Supports [giscus](https://github.com/laymonage/giscus), [utterances](https://github.com/utterance/utterances) or disqus
- [ ] Add important projects
  - Projects page
- [ ] Set up andtrack the SEO
  - SEO friendly with RSS feed, sitemaps and more!

## Sample posts

- [A markdown guide](https://tailwind-nextjs-starter-blog.vercel.app/blog/github-markdown-guide)
- [Learn more about images in Next.js](https://tailwind-nextjs-starter-blog.vercel.app/blog/guide-to-using-images-in-nextjs)
- [A tour of math typesetting](https://tailwind-nextjs-starter-blog.vercel.app/blog/deriving-ols-estimator)
- [Simple MDX image grid](https://tailwind-nextjs-starter-blog.vercel.app/blog/pictures-of-canada)
- [Example of long prose](https://tailwind-nextjs-starter-blog.vercel.app/blog/the-time-machine)
- [Example of Nested Route Post](https://tailwind-nextjs-starter-blog.vercel.app/blog/nested-route/introducing-multi-part-posts-with-nested-routing)

## Quick Start Guide

1. Try installing the starter using the new [Pliny project CLI](https://github.com/timlrx/pliny):

```bash
npm i -g @pliny/cli
pliny new --template=starter-blog my-blog
```

It supports the updated version of the blog with Contentlayer, optional choice of TS/JS and different package managers as well as more modularized components which will be the basis of the template going forward.

- [x] Personalize `siteMetadata.js` (site related information)
- [x] Modify the content security policy in `next.config.js` if you want to use any analytics provider or a commenting solution other than giscus.
- [x] Personalize `authors/default.md` (main author)

1. Modify `projectsData.js`
2. Modify `headerNavLinks.js` to customize navigation links
3. Add blog posts
4. Deploy on Vercel

## Installation

```bash
npm install
```

## Development

First, run the development server:

```bash
npm start
```

or

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Extend / Customize

`data/siteMetadata.js` - contains most of the site related information which should be modified for a user's need.

`data/authors/default.md` - default author information (required). Additional authors can be added as files in `data/authors`.

`data/projectsData.js` - data used to generate styled card on the projects page.

`data/headerNavLinks.js` - navigation links.

`data/logo.svg` - replace with your own logo.

`data/blog` - replace with your own blog posts.

`public/static` - store assets such as images and favicons.

`tailwind.config.js` and `css/tailwind.css` - contain the tailwind stylesheet which can be modified to change the overall look and feel of the site.

`css/prism.css` - controls the styles associated with the code blocks. Feel free to customize it and use your preferred prismjs theme e.g. [prism themes](https://github.com/PrismJS/prism-themes).

`components/social-icons` - to add other icons, simply copy an svg file from [Simple Icons](https://simpleicons.org/) and map them in `index.js`. Other icons use [heroicons](https://heroicons.com/).

`components/MDXComponents.js` - pass your own JSX code or React component by specifying it over here. You can then call them directly in the `.mdx` or `.md` file. By default, a custom link and image component is passed.

`layouts` - main templates used in pages.

`pages` - pages to route to. Read the [Next.js documentation](https://nextjs.org/docs) for more information.

`next.config.js` - configuration related to Next.js. You need to adapt the Content Security Policy if you want to load scripts, images etc. from other domains.

## Post

### Frontmatter

Frontmatter follows [Hugo's standards](https://gohugo.io/content-management/front-matter/).

Currently 7 fields are supported.

```
title (required)
date (required)
tags (required, can be empty array)
lastmod (optional)
draft (optional)
summary (optional)
images (optional, if none provided defaults to socialBanner in siteMetadata config)
authors (optional list which should correspond to the file names in `data/authors`. Uses `default` if none is specified)
layout (optional list which should correspond to the file names in `data/layouts`)
canonicalUrl (optional, canonical url for the post for SEO)
```

Here's an example of a post's frontmatter:

```
---
title: 'Introducing Tailwind Nexjs Starter Blog'
date: '2021-01-12'
lastmod: '2021-01-18'
tags: ['next-js', 'tailwind', 'guide']
draft: false
summary: 'Looking for a performant, out of the box template, with all the best in web technology to support your blogging needs? Checkout the Tailwind Nextjs Starter Blog template.'
images: ['/static/images/canada/mountains.jpg', '/static/images/canada/toronto.jpg']
authors: ['default', 'sparrowhawk']
layout: PostLayout
canonicalUrl: https://tailwind-nextjs-starter-blog.vercel.app/blog/introducing-tailwind-nextjs-starter-blog
---
```

### Compose

Run `node ./scripts/compose.js` to bootstrap a new post.

Follow the interactive prompt to generate a post with pre-filled front matter.

## Deploy

**Vercel**  
The easiest way to deploy the template is to use the [Vercel Platform](https://vercel.com) from the creators of Next.js. Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

**Netlify**
[Netlify](https://www.netlify.com/)’s Next.js runtime configures enables key Next.js functionality on your website without the need for additional configurations. Netlify generates serverless functions that will handle Next.js functionalities such as server-side rendered (SSR) pages, incremental static regeneration (ISR), `next/images`, etc.

See [Next.js on Netlify](https://docs.netlify.com/integrations/frameworks/next-js/overview/#next-js-runtime) for suggested configuration values and more details.

**GitHub Pages / Firebase etc.**  
As the template uses `next/image` for image optimization, additional configurations have to be made to deploy on other popular static hosting websites like [Firebase](https://firebase.google.com/) or [GitHub Pages](https://pages.github.com/). An alternative image optimization provider such as Imgix, Cloudinary or Akamai has to be used. Alternatively, replace the `next/image` component with a standard `<img>` tag. See [`next/image` documentation](https://nextjs.org/docs/basic-features/image-optimization) for more details.

The API routes used in the newsletter component cannot be used in a static site export. You will need to use a form API endpoint provider and substitute the route in the newsletter component accordingly. Other hosting platforms such as Netlify also offer alternative solutions - please refer to their docs for more information.

**Google App Engine**
Apart from changes mentioned above for `next/image`, configurations should be changed based on recommendations [here](https://github.com/vercel/next.js/discussions/12474#discussioncomment-17844) in order to set up the project for GAE deployment.

## Others who have used this template

- [Demo Blog](https://tailwind-nextjs-starter-blog.vercel.app/) - this repo
- [My personal blog](https://www.timlrx.com) - modified to auto-generate blog posts with dates
- [Aloisdg's cookbook](https://tambouille.vercel.app/) - with pictures and recipes!
- [GautierArcin's demo with next translate](https://tailwind-nextjs-starter-blog-seven.vercel.app/) - includes translation of mdx posts, [source code](https://github.com/GautierArcin/tailwind-nextjs-starter-blog/tree/demo/next-translate)
- [David Levai's digital garden](https://davidlevai.com/) - customized design and added email subscriptions
- [Thinh's Corner](https://thinhcorner.com/) - [customized layout](https://github.com/Th1nhNg0/th1nhng0.vercel.app/blob/5e73a420828d82f01e7147512a2c3273c4ec19f8/layouts/PostLayout.js) with sticky side table of contents
- [Leo's Blog](https://leohuynh.dev) - Tuan Anh Huynh's personal site. Add Snippets Page, Author Profile Card, Image Lightbox, ...
- [thvu.dev](https://thvu.dev) - Added `mdx-embed`, view count, reading minutes and more.
- [fiqrychoerudin.dev](https://www.fiqrychoerudin.dev/) - simple portfolio.
- [irvin.dev](https://www.irvin.dev/) - Irvin Lin's personal site. Added YouTube embedding.
- [KirillSo.com](https://www.kirillso.com/) - Personal blog & website.
- [ghali.dev](https://ghali.dev) - Cyril's Blog
- [DevBoy Blog](https://devboy.vercel.app/) - M.Reza's personal blog
- [slightlysharpe.com](https://slightlysharpe.com) - [Tincre's](https://tincre.com) main company blog
- [blog.b00st.com](https://blog.b00st.com) - [b00st.com's](https://b00st.com) main music promotion blog
- [astrosaurus.me](https://astrosaurus.me/) - Ephraim Atta-Duncan's Personal Blog
- [dhanrajsp.me](https://dhanrajsp.me/) - Dhanraj's personal site and blog.
- [blog.r00ks.io](https://blog.r00ks.io/) - Austin Rooks's personal blog ([source code](https://github.com/Austionian/blog.r00ks)).
- [honghong.me](https://honghong.me) - Tszhong's personal website ([source code](https://github.com/tszhong0411/home))
- [alfoncode.com](https://alfoncode.com) - Alfonso García's personar website. Customized design ([source code](https://github.com/alfoncode/personal-web))
- [marceloformentao.dev](https://marceloformentao.dev) - Marcelo Formentão personal website ([source code](https://github.com/marceloavf/marceloformentao.dev)).
- [abiraja.com](https://www.abiraja.com/) - with a [runnable JS code snippet component!](https://www.abiraja.com/blog/querying-solana-blockchain)
- [einargudni.com](https://www.einargudni.com) - with a customized theme, command pallette and more ([source code](https://github.com/einargudnig/einargudni.com))
- [bpiggin.com](https://www.bpiggin.com) - Ben Piggin's personal blog
- [maqib.cn](https://maqib.cn) - A blog of Chinese front-end developers 狂奔小马的博客 ([源码](https://github.com/maqi1520/nextjs-tailwind-blog))
- [ambilena.com](https://ambilena.com/) - Electronic Music Blog & imprint for upcoming musicians.
- [kittan.ru](https://www.kittan.ru/) - Kittanb's personal blog about linux ([source code](https://github.com/kittanb/blog))
- [nchristopher.me](https://nchristopher.me) - Nicholas Christopher's personal website and blog ([source code](https://github.com/nchristopher/blog))
- [dalelarroder.com](https://dalelarroder.com) - Dale Larroder's personal website and blog ([source code](https://github.com/dlarroder/dalelarroder))
- [devahoy.com](https://devahoy.com) - Chai's personal blog (Thai language)
- [0xchai.io](https://0xchai.io) - Chai's personal blog
- [techipedia](https://techipedia.vercel.app) - Simple blogging progressive web app with custom installation button and top progress bar
- [reubence.com](https://reubence.com) - Reuben Rapose's Digital Garden
- [axolo.co/blog](https://axolo.co/blog) - Engineering management news & axolo.co updates (with image preview for article in the home page)
- [musing.vercel.app](https://musing.vercel.app/) - Parth Desai's personal blog ([source code](https://github.com/pycoder2000/blog))
- [onyourmental.com](https://www.onyourmental.com/) - [Curtis Warcup's](https://github.com/Cwarcup) website for the On Your Mental Podcast ([source code](https://github.com/Cwarcup/on-your-mental))
- [cwarcup.com](https://www.cwarcup.com/) - Curtis Warcup's personal website and blog ([source code](https://github.com/Cwarcup/personal-blog).
- [ondiek-elijah.me](https://www.ondiek-elijah.me/) - Ondiek Elijah's website and blog ([source code](https://github.com/Dev-Elie/ondiek-elijah)).
- [jmalvarez.dev](https://www.jmalvarez.dev/) - José Miguel Álvarez's personal blog ([source code](https://github.com/josemiguel-alvarez/nextjs-blog))
- [justingosses.com](https://justingosses.com/) - Justin Gosses's personal website and blog ([source code](https://github.com/JustinGOSSES/justingosses-website))
- [sabare.me](https://sabare.me/) - Victor Sabare's personal website and blog ([source code](https://github.com/Sabareh/blog)
- [https://bitoflearning-9a57.fly.dev/](https://bitoflearning-9a57.fly.dev/) - Sangeet Agarwal's personal blog, replatformed to [remix](https://remix.run/remix) using the [indie stack](https://github.com/remix-run/indie-stack) ([source code](https://github.com/SangeetAgarwal/bitoflearning)) WIP
- [raphaelchelly.com](https://www.raphaelchelly.com/) - Raphaël Chelly's personal website and blog ([source code](https://github.com/raphaelchelly/raph_www))

## Support

Using the template? Support this effort by giving a star on GitHub, sharing your own blog and giving a shoutout on Twitter or becoming a project [sponsor](https://github.com/sponsors/timlrx).

## Licence

[MIT](https://github.com/timlrx/tailwind-nextjs-starter-blog/blob/master/LICENSE) © [Timothy Lin](https://www.timlrx.com)
