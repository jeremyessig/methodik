# Methodik

## _A blocks CSS framework_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/jeremyessig/Methodik)

Methodik is a CSS framework based on the BEM syntax and on the blocks architecture. It brovides a bunch of css classes and strcutres pre-build.

## Features

- Strong HTML tree structure based on the BEM syntax.
- Build your website with pre-build blocks.
- Customize your website with a custom scss theme file.
- Create custom themes and share them with our community.
- Use our Methodik syntax in your HTML files and simplify your css files
- Much more !!!

## Tech

Methodik uses a number of open source projects to work properly:

- Sass/SCSS!
- Javascript
- HTML5 & CSS3

And of course Methodik itself is open source.

## Installation

Methodik requires Sass/SCSS (https://sass-lang.com/) to run.

Install the dependencies from the current github and copy/past it on your website folder.

From your website folder, open a terminal and run this command:

```bash
sass --watch Methodik/export.scss:Methodik.css --style compressed
```

## Methodik syntax

Methodik provides a custom syntax based on BEM. You can easily integrate it into your HTML files. Methodik classes are all prefixed with mk- to differentiate them from personal classes that you would add to your project.

Example of a Methodik blocks

```html
<section class="mk-section" id="sectionExample">
  <div class="mk-section__header">
    <div class="mk-box">
      <div class="mk-box__title">
        <h1>Hello</h1>
      </div>
      <div class="mk-box__subtitle">
        <h2>world !</h2>
      </div>
    </div>
  </div>
  <div class="mk-section__body">
    <div class="mk-box --flex-row">
      <div class="mk-box__text">
        <p>Methodik is awsome and I love it !</p>
      </div>
      <div class="mk-box__text">
        <p>
          With Methodik you can create beautiful websites with very little css
          code.
        </p>
      </div>
    </div>
  </div>
  <div class="mk-section__footer">
    <div class="mk-box">
      <div class="mk-box__link">
        <a href="#"> Follow us</a>
      </div>
    </div>
  </div>
</section>
```

## HTML blocks and elements

> Note: All blocks are prefixed by `mk-`.

#### Header

```html
<header class="mk-header" id="headerExample">
  <div class="mk-header__top"></div>
  <div class="mk-header__center"></div>
  <div class="mk-header__bottom"></div>
</header>
```

#### Section

```html
<section class="mk-section" id="sectionExample">
  <div class="mk-section__header"></div>
  <div class="mk-section__body"></div>
  <div class="mk-section__footer"></div>
</section>
```

#### Article

```html
<article class="mk-article" id="articleExample">
  <div class="mk-article__header"></div>
  <div class="mk-article__body"></div>
  <div class="mk-article__footer"></div>
</article>
```

#### Box

```html
<div class="mk-box" id="boxExample">
  <div class="mk-box__title"></div>
  <div class="mk-box__subtitle"></div>
  <div class="mk-box__text"></div>
  <div class="mk-box__img"></div>
  <div class="mk-box__thumbnail"></div>
</div>
```

## Modificators

#### Layouts

| Class                         | Behaviour | Compatible blocks                  |
| ----------------------------- | --------- | ---------------------------------- |
| `--flex-col`                  |           | `mk-section` `mk-article` `mk-box` |
| `--flex-col-reverse`          |           | `mk-section` `mk-article` `mk-box` |
| `--flex-row`                  |           | `mk-section` `mk-article` `mk-box` |
| `--flex-row-reverse`          |           | `mk-section` `mk-article` `mk-box` |
| `--flex-center`               |           | `mk-section` `mk-article` `mk-box` |
| `--flex-top-center`           |           | `mk-section` `mk-article` `mk-box` |
| `--flex-bottom-center`        |           | `mk-section` `mk-article` `mk-box` |
| `--flex-center-left`          |           | `mk-section` `mk-article` `mk-box` |
| `--flex-center-right`         |           | `mk-section` `mk-article` `mk-box` |
| `--flex-top-left`             |           | `mk-section` `mk-article` `mk-box` |
| `--flex-top-right`            |           | `mk-section` `mk-article` `mk-box` |
| `--flex-top-space-between`    |           | `mk-section` `mk-article` `mk-box` |
| `--flex-bottom-left`          |           | `mk-section` `mk-article` `mk-box` |
| `--flex-bottom-right`         |           | `mk-section` `mk-article` `mk-box` |
| `--flex-bottom-space-between` |           | `mk-section` `mk-article` `mk-box` |

#### Images and thumbnailes

| Class               | Behaviour | Compatible blocks                 |
| ------------------- | --------- | --------------------------------- |
| `--size-smaller`    |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-small`      |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-medium`     |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-large`      |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-larger`     |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-x-larger`   |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-xx-larger`  |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-xxx-larger` |           | `mk-box__img` `mk-box__thumbnail` |
| `--size-banner`     |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-1-1`       |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-4-3`       |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-3-4`       |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-5-3`       |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-3-5`       |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-16-9`      |           | `mk-box__img` `mk-box__thumbnail` |
| `--ratio-9-16`      |           | `mk-box__img` `mk-box__thumbnail` |

## License

Open Source and free

**Free Software, Hell Yeah!**
