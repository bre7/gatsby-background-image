<h1 align="center">
  gatsby-background-image(-es5)
</h1>
<p align="center">
  <i>Speedy, optimized <strong>background</strong>-images without the work!</i>
</p>
<p align="center">
  <a href="https://github.com/timhagn/gatsby-background-image/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="gatsby-background-image is released under the MIT license." />
  </a>
  <a href="https://circleci.com/gh/timhagn/gatsby-background-image">
    <img src="https://circleci.com/gh/timhagn/gatsby-background-image.svg?style=shield" alt="Current CircleCI build status of gatsby-background-image." />
  </a>
  <a href="https://codecov.io/gh/timhagn/gatsby-background-image">
    <img src="https://codecov.io/gh/timhagn/gatsby-background-image/branch/master/graph/badge.svg" />
  </a>
  <a href="https://www.npmjs.org/package/gatsby-background-image">
    <img src="https://img.shields.io/npm/v/gatsby-background-image.svg" alt="Current npm package version." />
  </a>
  <a href="https://npmcharts.com/compare/gatsby-background-image?minimal=true">
    <img src="https://img.shields.io/npm/dw/gatsby-background-image.svg" alt="Downloads per week on npm." />
  </a>
  <a href="https://github.com/timhagn/gatsby-background-image/blob/master/CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
  <a href="https://lerna.js.org/">
    <img src="https://img.shields.io/badge/maintained%20with-lerna-0a7bbb.svg" alt="Lerna badge." />
  </a>  
</p>

`gatsby-background-image` & `gatsby-background-image-es5` are React components
which for background-images provide, what Gatsby's own `gatsby-image` does for
the rest of your images and even more:  
**Now with [Art-Direction support](#how-to-use-with-art-direction-support)!**

It has all the advantages of [gatsby-image](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-image),
including the "blur-up" technique or a "[traced placeholder](https://github.com/gatsbyjs/gatsby/issues/2435)"
SVG to show a preview of the image while it loads,  
**plus** being usable as a container (no more hacks with extra wrappers)  
**plus** being able to work with [multiple stacked background images](#how-to-use-with-multiple-images)  
**plus** being able to style with [Tailwind CSS and suchlike Frameworks](#tailwind-css-and-suchlike-frameworks)

All the glamour (and speed) of `gatsby-image` for your Background Images!

_*Of course styleable with `styled-components` and the like!*_

## Preamble

Since `gatsby-background-image@0.6.0`, this is a monorepo managed by
[`lerna`](https://lerna.js.org/), so have a look at the individual READMEs of

- [`gatsby-background-image`](https://github.com/timhagn/gatsby-background-image/tree/master/packages/gatsby-background-image#readme)
- [`gatsby-background-image-es5`](https://github.com/timhagn/gatsby-background-image/tree/master/packages/gatsby-background-image-es5#readme)

## Example Repo

`gatsby-background-image` has an example repository to see it's similarities
& differences to `gatsby-image` side by side.  
It's located at: [gbitest](https://github.com/timhagn/gbitest)
To use it with `gatsby-background-image-es5` change the dependency there.

## Contributing

Everyone is more than welcome to contribute to this little package!  
Docs, Reviews, Testing, Code - whatever you want to add, just go for it : ).
So have a look at our [CONTRIBUTING](CONTRIBUTING.md) file and give it a go.
Thanks in advance!

## TODO

_For anything you may think necessary tell me by opening an issue or a PR : )!_
