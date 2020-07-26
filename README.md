# [WordPress Theme - Aquila](https://youtu.be/lNtw4yxEydM) 🎨
[![Project Status: WIP – Initial development is in progress.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip) [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

* A WordPress theme Project for Advanced WordPress Theme Development Course.
This theme uses Bootstrap. [Learn](https://www.youtube.com/playlist?list=PLD8nQCAhR3tT3ehpyOpoYeUj3KHDEVK9h) to build an Advanced WordPress Theme from scratch

<a href="https://codeytek.com/course/advanced-wordpress-theme-development-course/" target="_blank">
<img src="https://codeytek.com/wp-content/uploads/2020/07/banner.png" alt="WordPress theme development banner" />
</a>

## [Tutorial Course](https://codeytek.com/course/advanced-wordpress-theme-development-course/)

## Features

- ![](demo/features-one.png)

- ![](demo/features-two.png)

- Custom front page.
- Custom Blog page with posts displayed in grid format using bootstrap.

## Maintainer

| Name                                                   | Github Username |
|--------------------------------------------------------|-----------------|
| [Imran Sayed](mailto:codeytek.academy@gmail.com)       |  @imranhsayed   |

## Usage

1. Clone the WordPress theme [aquila](https://github.com/imranhsayed/aquila) in your WordPress
themes directory and activate it.

## Dashboard Setup.

1. Create pages called 'Home' and 'Blog' and set them from Appearance > Customizer > Homepage Settings like so:

- ![](demo/home-page-customizer-setup.png)

## Development ( To be added )

Below features will be added later ( TODO )

**Install**

Clone the repo and run

```bash
cd aquila/assets
npm install
```

**During development**

```bash
npm run dev
```

**Production**

```bash
npm run prod
```

**Linting & Formatting** ( TO BE ADDED )

The following command will fix most errors and show and remaining ones which cannot be fixed automatically.

```bash
npm run eslint:fix
```

We follow the stylelint configuration used in WordPress Gutenberg, run the following command to lint and fix styles.

```bash
npm run stylelint:fix
```

Format code with prettier

```bash
npm run format-js
```

Directory Structure

```php
.
├── README.md
├── assets
│   ├── main.js
│   └── src
│       └── library
│           ├── css
│           │   ├── bootstrap-grid.min.css
│           │   └── bootstrap.min.css
│           └── js
│               └── bootstrap.min.js
├── demo
│   ├── banner.png
│   ├── blog-page.png
│   ├── features-one.png
│   ├── features-two.png
│   └── home-page-customizer-setup.png
├── footer.php
├── front-page.php ( Home Page )
├── functions.php
├── header.php
├── inc
│   ├── classes
│   │   ├── class-aquila-theme.php
│   │   ├── class-assets.php
│   │   ├── class-menus.php
│   │   └── class-meta-boxes.php
│   ├── helpers
│   │   ├── autoloader.php
│   │   └── template-tags.php
│   └── traits
│       └── trait-singleton.php
├── index.php ( Blog page )
├── page.php  ( Single Page )
├── screenshot.png
├── single.php ( Single Post Page )
├── style.css
└── template-parts
    ├── components
    │   └── blog
    │       ├── entry-content.php
    │       ├── entry-footer.php
    │       ├── entry-header.php
    │       └── entry-meta.php
    ├── content-none.php
    ├── content.php
    └── header
        └── nav.php
```
