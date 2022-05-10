# 💻 Bitcamp's 2022 Website
The main website for registering for Bitcamp 2022. It is built using [Bootstrap 5](https://getbootstrap.com/).

## 🗺️ Project Layout
- [`index.html`](/index.html): The landing page
- [`bitcamp-brand/`](bitcamp-brand/): A [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) with Bitcamp's standard fonts, logos, favicons, and other common brand info
- [`assets/`](/assets): For all custom images, CSS, etc.

## 🚀 Quick start
To get started with development:
- Clone this repository
```bash
git clone --recurse-submodules https://github.com/bitcamp/bitcamp-site-2022
```
- Download the [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) VSCode extension
  - It is an extension that makes your HTML look beautiful on save 💅
  - If you don't use VSCode, scroll down to the plugins section of the [js-beautify website](https://beautifier.io/) and find the plugin for your editor of choice.

## ❓ FAQ
- Someone else modified the `bitcamp-brand` submodule version. How do I get those changes (`git pull` alone doesn't work)?
```bash
git submodule update --init --recursive
```
- The [`bitcamp-brand`](https://github.com/bitcamp/bitcamp-brand) repo updated. How do I pull those changes into this repo?
```bash
git submodule update --remote
```

## 🔗 Useful Resources
### The Basics
- **[Shay Howe's Intro to HTML and CSS](http://learn.shayhowe.com/html-css/)**
- [freecodecamp (web dev course)](http://www.freecodecamp.com/)

### Documentation
- [Bootstrap](https://getbootstrap.com/docs/)
- [Mozilla Developer Network (MDN)](https://developer.mozilla.org/en-US/)
- [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### Inspiration
- [CodePen](https://codepen.io/)
- [CSS-Tricks](https://css-tricks.com/)
