# CodePen exercise 04 - Documentation page

## What I'm building
Bogus documentation page for FreeCodeCamp's exercise. There's a live, tweakable demo at [this CodePen](https://codepen.io/minicarbonara/pen/YzqXBbR).

## Requirements (per assignment)
To make a **documentation page** featuring:
- A `<main>` element with id="main-doc" holding the main content
- Within main-doc, at least 5 `<section>` elements with class="main-section"
- Each of them with a `<header>` element with the section's topic
- Also with an individual id="Name_of_section" (underscores for spaces)
- The .main-section elements should have at least 10 `<p>` elements total
- They should also have at least 5 `<code>` elements total
- Also at least 5 `<li>` elements total (not each)
- A `<nav>` element with id="navbar"
- Inside navbar, a `<header>` element with the topic at the beginning
- Also `<a>` elements with class="nav-link" to each .main-section element, with text corresponding to the `<header>` of each section, linked to it
- .navbar should be on the left and always visible
- There has to be at least one media query


## How I'm planning it to look, and why
Main reference: example from [FreeCodeCamp's CodePen](https://codepen.io/freeCodeCamp/full/NdrKKL) passing all tests from this exercise. But... let's make it FUN (and innecesarily painful), shall we? Since coding is the closest there is to arcane magic (you write some obscure words in the right order and stuff happens) let's turn this documentation page into a spellbook explaining 5 different spells. We'll need appropiate fonts, colors... maybe even hover animations! We'll be here *FOREVER*.

The main reference for the Spellbook might be [this markdown tool for D&D content](https://homebrewery.naturalcrit.com/) that takes plain text and turns it into Dungeons & Dragons 5th edition pages. The structure will be something like this.

 	![image pending](http://static.skaip.org/img/emoticons/180x180/f6fcff/manshrug.gif)

The structure will have to be the same (menu on the left, content on the right, sections...) but we will style the text and box elements differently than the example. **This looks like a chance to try the CSS grid too.**

## Steps (functional -> technical)

### 1. Setting the structure (CSS grid)
First off let's create the documents themselves and set the two areas in the grid: nav and main:
- Create the HTML and CSS files. Set the DOCTYPE, `<head>` and `<body>` elements
- Set the `<nav>` and the `<main>` elements with their IDs
- Apply some garish colors to the BG and sections for visibility
- Define a CSS Grid to hold the `<nav>` and the `<main>`, and assign them
- Create a sample `<section>` with a `<header>`, a `<code>` and two `<p>` elements, plus class and ID
- Create a sample #nav-link on the `<nav>` pointing to the sample section. Try it
- Set a footer at the bottom of `<nav>` for copyright

### 2. Styling the basic components
- Adjust the sizes, margins and paddings of the nav-bar and section blocks
- Select and import an appropiate Google Font for titles and another for copy text.
- Set a background-color for the nav-bar, the main, and the sections
- Set a media query for VP width below 600px

### 3. Filling in the content
- Clone the sample section 4 times, adding an `<ul>` and an `<ol>` to two different clones
- Clone the sample #nav-link and update titles and links

### 4. Further styling the content 
- Set text colors for `<header>`, `<p>`, `<li>`, `<a>` and .nav-link (with hover)
- Set bg colors, font-family and text color for `<code>`
- *Optional* Check if you can do Capitular letters for `<p>`
- *Optional* Try a simple hover animation for .nav-link

