---
title: Setting Up a Gatsby Blog
date: "2019-04-28T19:30:00.000Z"
layout: post
draft: false
path: "/posts/blog_setup/"
category: "Marcus"
tags:
  - "Tech"
  - "Gatsby"
  - "Now.sh"
  - "GitHub"
  - "Development"
description: "How I setup a blog with Gatsby, Deployed it using Now.sh, and write posts from my iPhone with Markdown"
---

# [GatsbyJS](https://www.gatsbyjs.org/)

This blog is built using a Javascript framework called GatsbyJS. Gatsby is probably overkill for what I'm doing, but with the little development knowledge I have, I found it easy to use Gatsby with a starter template to build a static site. Their documentation and the community that is adopting Gatsby have also been a big help in getting started. Gatsby boasts on their website that this is the future of the web, and delivers the fastest website possible based on your content.

## Install

Before you get into this you should have some familiarity with your command line. Gatsby requires [Node.js](https://www.gatsbyjs.org/tutorial/part-zero/#install-nodejs) and it is recommended that you use [git](https://www.gatsbyjs.org/tutorial/part-zero/#install-git) during development of your site. Once you satisfy these dependencies, you can install the Gatsby CLI by running...
```bash
npm install -g gatsby-cli
```

## Getting Started

To get started, in the command line you'll type...

```bash
gatsby new [SITE_DIRECTORY_NAME] [URL_OF_STARTER_GITHUB_REPO]
```

This will create a new site for you with the starter as a starting point. I personally liked the styling of [Lumen v2](https://github.com/GatsbyCentral/gatsby-v2-starter-lumen) so I started there. From this point you can modify the files locally in your favorite text editor. I use [Atom](https://atom.io/). To see your changes locally you can save your file locally and type `gatsby develop`. Once the the command finishes, you can visit `localhost:8000` in your favorite browser and navigate your new site. Cool, right?!?

## Deploying

Once you've modified and personalized the starter, you'll want to show other people. To deploy your site, you can use a number of different tools. Gatsby lists many static web hosts on their site (AWS Amplify, Netlify, GitHub Pages, Surge.sh, Aerobatic, Now.sh). I only have experience with [Now.sh](https://zeit.co/now). I find that it is easy to use, well-documented, and **free** for what I need. [Signup](https://zeit.co/signup) is easy. Once you've [installed Now](https://zeit.co/docs/v2/getting-started/installation/), I'd recommend playing around with some of their [examples](https://github.com/zeit/now-examples) on GitHub. Pull the repository to your local machine and try to deploy a few of the examples with now. Once you get the hang of it, check out the guide they have for [Zeit Gatsby Deploys](https://zeit.co/guides/deploying-gatsby-with-now).

## Updates

So its deployed... how will I make updates? On my next trip, I'll be traveling without my computer. I have not yet decided if I'll be bringing my iPad mini or not, but I plan to rely on my iPhone. Thankfully, [Now has a GitHub integration](https://zeit.co/github) to deploy projects automatically from pull request. This integration, paired with [Working Copy](https://workingcopyapp.com/) should allow me to create a new blog post and publish it to Now _with ease_.

Here's my workflow for writing a blog post with Working Copy:
- open [my repository](https://github.com/marcusalfred/onebagging-gatsby-now) in Working Copy
- create a new branch for my new post
- navigate to `/src/pages/articles`
- tap the ` + ` button and create a new directory
- copy the file from the template directory and paste into the new directory.
- write my blog using this template
- commit these changes & push to remote
- create a new pull request on the github mobile site
- check this pull request in a few minutes for a new Now.sh staging deploy
- confirm the blog appears and any changes were made
- merge pull request
- confirm post is live at https://bagging.one
