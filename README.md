# Kyle Rubenok's Public Blog

A fork of the lovel Lumen Gatsby Starter by [Alexander Shelepenok](https://github.com/alxshelepenok/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/9e57fe74-aa05-48c7-9e40-70dbeb41899d/deploy-status)](https://app.netlify.com/sites/blog-rubenok/deploys)
[![codecov](https://codecov.io/gh/krubenok/blog/branch/master/graph/badge.svg)](https://codecov.io/gh/krubenok/blog) 
[![Maintainability](https://api.codeclimate.com/v1/badges/01cb24fccd0f37c8f428/maintainability)](https://codeclimate.com/github/krubenok/blog/maintainability) 
[![Test Coverage](https://api.codeclimate.com/v1/badges/01cb24fccd0f37c8f428/test_coverage)](https://codeclimate.com/github/krubenok/blog/test_coverage)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fkrubenok%2Fblog.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fkrubenok%2Fblog?ref=badge_shield)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e33226810af945e0965065b7846abba3)](https://app.codacy.com/app/krubenok/blog?utm_source=github.com&utm_medium=referral&utm_content=krubenok/blog&utm_campaign=Badge_Grade_Settings)
[![Netlify Status](https://api.netlify.com/api/v1/badges/9e57fe74-aa05-48c7-9e40-70dbeb41899d/deploy-status)](https://app.netlify.com/sites/blog-rubenok/deploys)
[![codecov](https://codecov.io/gh/krubenok/blog/branch/master/graph/badge.svg)](https://codecov.io/gh/krubenok/blog)

## Features

[Lost Grid](http://lostgrid.org).
[Modern font stack](https://bitsofco.de/the-new-system-font-stack).
Beautiful typography inspired by [matejlatin/Gutenberg](https://github.com/matejlatin/Gutenberg).
Syntax highlighting in code blocks using [PrismJS](http://prismjs.com).
[Mobile-First](https://medium.com/@mrmrs_/mobile-first-css-48bc4cc3f60f) approach in development.
Archive organized by tags and categories.
Pagination support.
[Netlify CMS](https://www.netlifycms.org) support.
Google Analytics.
Disqus Comments.
[Flow](https://flow.org/) static type checking.

## Web Performance Tests

Lighthouse Report - [WebPageTest](https://www.webpagetest.org/result/190724_M7_f1bbaffa9a99796d855240e4ba17be3a/)
Visual Comparison - [WebPageTest](https://www.webpagetest.org/result/190724_QH_353a4b3856bce2ff4ac8319506e5fce8/1/details/)

## Quick Start

### Create a Gatsby site

Use the Gatsby CLI to create a new site, specifying the Lumen starter.

```sh
# Create a new Gatsby site using the Lumen starter
gatsby new blog https://github.com/alxshelepenok/gatsby-starter-lumen
```

### Start Developing

Navigate into your new site’s directory and start it up.

```sh
cd blog
gatsby develop
```

### Open the source code and start editing

Your site is now running at `http://localhost:8000`!

Note: You'll also see a second link: `http://localhost:8000/___graphql`. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql).

Open the `blog` directory in your code editor of choice and edit `src/templates/index-template.js`. Save your changes and the browser will update in real time!

#### Access Locally

```shell
git clone https://github.com/[GITHUB_USERNAME]/[REPO_NAME].git
cd [REPO_NAME]
yarn
$ npm run develop
```

To test the CMS locally, you'll need run a production build of the site:

```shell
npm run build
gatsby serve
```

## License

The MIT License (MIT)

Copyright (c) 2019 Kyle Rubenok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
