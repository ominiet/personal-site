# Oscar Miniet Personal Website

A personal website for Oscar Miniet to use as a portfolio and playground

## Quick Start

The project uses only Node/Yarn and its dependencies listed in the package.json file.
Currently, I am using Node 11.8.0 and Yarn 1.13.0. In order to run the project you 
must first download node and yarn. You can do so by visiting [node](https://nodejs.org)
and [yarn](https://yarnpkg.com) and downloading the appropriate installer for your 
system. If you have a package installer you can install both through that. Here 
are some examples:

#### Mac
`brew install node`

`brew install yarn`

#### Arch Linux
`sudo pacman -S node yarn`

After Node and Yarn are installed, navigate to the cloned directory and run:

`yarn`

This will download all _package.json_ dependencies. Now you will be ready to start the
project with:

`yarn run frontend`

## Technologies Used

This section will be a brief description of the technologies I chose to work with and
what I hope to learn by using them.

#### [Node](https://nodejs.org/)

Chosen because I specifically wanted to make a React-based project for personal learning.

#### [Yarn](https://yarnpkg.com/)

Chosen as a substitute for NPM. At the time of this repository's creation, yarn and npm
both seem to have similar features in terms of caching and lockfiles as far as I have
read, but using yarn to switch it up.

#### [React](https://reactjs.org/)

Chosen because React is one of the fastest growing frontend libraries in terms of 
popularity. While this project will likely not be as interactive as a typical web
application, I chose to still implement React so that I can familiarize myself with
the libraries and syntax as practice.

#### [Webpack](https://webpack.js.org/)

Mainly chosen because I did not want to rely on 
[create-react-app](https://github.com/facebook/create-react-app) because I wanted
a better understanding of how to work with React from scratch should I want to do so for
a future project. The process of bundling and optimizing files also seemed interesting to
me as well, because it is something I feel was not emphasized in school projects.

Additionally, Babel seems to be required to convert ES6 to ES5 for react projects, and
Webpack appears to be the most popular tool to implement that cross-compile functionality

#### [Express](https://expressjs.com/)

Chosen because I have worked with Express in the past, but still feel like I should hone
my skills more. Currently, express is used to serve the bundled react-app when deployed.
As ideas for more functionality are created, I may need to create a REST API to accompany
the frontend, which I plan to implement with Express. I may decide later on to switch to
some other framework such as Spring just to try it out.

#### [Heroku](https://heroku.com/)

Chosen because it is quick and easy to get an express application up and running. I may
switch later to AWS, because I feel there is more learning potential there.