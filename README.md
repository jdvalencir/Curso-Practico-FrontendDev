# Curso-Practico-FrontendDev

Static HTML/CSS screens for an online-store UI, built while following Platzi's practical Frontend course. Each `classN.html` file is a snapshot of the project at a given class of the course, so the history of the layout can be followed step by step.

## Features

Screens implemented across the class files (HTML and CSS only, no JavaScript):

- Password recovery: "Create a new password" (`class1.html`) and "Email has been sent!" (`class2.html`)
- Login form with email, password and sign-up button (`class3.html`)
- "My account" pages (`class4.html`, `class5.html`)
- Product card grid with add-to-cart icons (`class6.html`)
- Desktop dropdown menu: My orders, My account, Sign out (`class7.html`)
- Navbar with menu icon, user email and shopping cart (`class11.html`)
- Order pages: "My order" (`class9.html`) and "My orders" (`class10.html`)
- Product detail side panel with an add-to-cart button (`class12.html`)

`index.html` is an empty starter page that defines the color variables and the Quicksand font. `class8.html` is also present in the repository.

## Tech stack

- HTML5
- CSS (inline `<style>` blocks, CSS custom properties)
- Google Fonts (Quicksand)
- SVG/PNG icons and logos

## Project structure

```
index.html        Starter page (color variables and font)
class1..12.html   Course snapshots, one per class
icons/            Cart, menu, close and arrow icons
logos/            Logos and favicons
```

## Getting started

There is no build step or dependency. Clone the repository and open any HTML file in a browser:

```sh
git clone https://github.com/jdvalencir/Curso-Practico-FrontendDev.git
cd Curso-Practico-FrontendDev
xdg-open class12.html   # or open the file manually
```

An internet connection is needed to load the Google Fonts stylesheet.

## Context

Practice project for the Platzi practical Frontend course.
