# CodePen exercise 04 - Documentation page

## What I'm building
Bogus documentation page.

## Requirements (per assignment)
To make a **documentation page** featuring:
- A < main> element with id="main-doc" holding the main content
- Within main-doc, at least 5 < section> elements with class="main-section"
- Each of them with a < header> element with the section's topic
- Also with an individual id="Name_of_section" (underscores for spaces)
- The .main-section elements should have at least 10 < p> elements total
- They should also have at least 5 < code> elements total
- Also at least 5 < li> elements total (not each)
- A < nav> element with id="navbar"
- Inside navbar, a < header> element with the topic at the beginning
- Also < a> elements with class="nav-link" to each .main-section element, with text corresponding to the < header> of each section, linked to it
- .navbar should be on the left and always visible
- There has to be at least one media query


## How I'm planning it to look, and why
Main reference: example from [FreeCodeCamp's CodePen](https://codepen.io/freeCodeCamp/full/NdrKKL) passing all tests from this exercise. But... let's make it FUN (and innecesarily painful), shall we? Since coding is the closest there is to arcane magic (you write some obscure words in the right order and stuff happens) let's turn this documentation page into a spellbook explaining 5 different spells. We'll need appropiate fonts, colors... maybe even hover animations! We'll be here *FOREVER*.

The structure will have to be the same (menu on the left, content on the right, sections...) but we will style the text and box elements differently than the example. This looks like a chance to try the CSS grid too.

## Steps
### Setting the basic content and structure
1. Create the HTML and CSS files. Set the DOCTYPE, < head> and < body> elements
2. Set the < nav> and the < main> elements with their IDs
3. Create a sample < section> with a < header>, a < code> and two < p> elements, plus class and ID
4. Create a sample #nav-link on the < nav> pointing to the sample section
5. Define a CSS Grid to hold the < nav> and the < main>, and assign them
6. Clone the sample section 4 times, adding an < ul> and an < ol> to two different clones
7. Clone the sample #nav-link and update titles and links
8. Set a footer at the end of < nav> for shits and giggles (and copyright)

### Styling the shit out of it
9. Select and import an appropiate Google Font for titles and another for copy text.
10. Set a background-color for the nav-bar, the main, and the sections
11. Set text colors for < header>, < p>, < li>, < a> and .nav-link (with hover)
12. Set bg colors, font-family and text color for < code>
13. Adjust grid sizes and < section> spacing
14. Check if you can do Capitular letters for < p>
15. Try a simple hover animation for .nav-link

### Adding media queries for responsive layout
16. Add a media query putting the nav-bar on top (and hiding or moving the copyright footer) 
