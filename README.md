<!-- AUTOMATION BADGES -->

[![Build and Deploy](https://github.com/webceyhan/bs-splendid-food/actions/workflows/github-pages.yaml/badge.svg)](https://github.com/webceyhan/bs-splendid-food/actions/workflows/github-pages.yaml)

<!-- LOGO (OPTIONAL) -->

<!-- ![Logo](./logo.png) -->

 <!-- HEADER ///////////////////////////////////////////////////////////// -->

# Bootstrap Splendid Food Application

This is a very simple online grocery shop application built with Bootstrap.
Its purpose is to demonstrate the use of Bootstrap components and customize them using SaSS. Then you can compile and minify the CSS and JS files.

[View Demo](https://github.com/webceyhan/bs-splendid-food) |
[Report Issue](https://github.com/webceyhan/bs-splendid-food/issues) |
[Request Feature](https://github.com/webceyhan/bs-splendid-food/pulls) |
[@webceyhan](https://twitter.com/webceyhan)

<br>
<!-- REQUIREMENTS /////////////////////////////////////////////////////// -->

## Requirements

You need to install the [Node.js](https://nodejs.dev/)
and `npm` package manager first.

> Recommended IDE:
> [VSCode](https://code.visualstudio.com/)

<br>
<!-- INSTALLATION //////////////////////////////////////////////////////// -->

## Installation

1. Clone the repository.
    ```sh
    git clone https://github.com/webceyhan/bs-splendid-food.git
    ```
2. Get inside the cloned project folder.
    ```sh
    cd bs-splendid-food
    ```
3. Install NPM packages.
    ```sh
    npm install
    ```

<br>
<!-- USAGE /////////////////////////////////////////////////////////////// -->

## Usage

You can use following commands to do various task with the project.

```sh
npm run dev         # start development server
npm run build       # build for production
npm run previw      # build and preview for production
```

> Take a look at the other scripts in [`package.json`](./package.json)

<br>
<!-- DEVELOPMENT ///////////////////////////////////////////////////////// -->

## Development

Start the development server to watch changes while you code.

```sh
npm run dev
```

<br>
<!-- BUILDING //////////////////////////////////////////////////////////// -->

## Building

Build the application for production.

```sh
npm run build
```

Build and preview the application for production.

```sh
npm run previw
```

<br>
<!-- DEPLOYMENT ////////////////////////////////////////////////////////// -->

## Deployment

A GitHub Action will automatically deploy the project to GitHub Pages on every push.

The workflow will build the project using npm and output the result to the `dist` folder which will be then pushed to the `gh-pages` branch.

> See the details in [.github/workflows/github-pages.yml](./.github/workflows/github-pages.yml)

<br>
<!-- REFERENCES ////////////////////////////////////////////////////////// -->

## References

-   [Node.js](https://nodejs.dev/)
-   [Bootstrap](https://getbootstrap.com)
-   [SaSS](https://sass-lang.com/)
-   [GitHub Actions](https://docs.github.com/en/actions)
    -   [GitHub Pages](https://pages.github.com/)
    -   [github-pages-deploy-action](https://github.com/JamesIves/)
