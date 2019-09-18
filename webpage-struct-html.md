# Read 04: Structure web pages with HTML
## Duckett: HTML & CSS, Chapter 18 - Process & Design
- Understand your **target audience**
  - *Who are they?*
  - *Why would they come to your site?*
  - *What information do they need?*
  - *When are they likley to return?*
- Make a **site map** to plan the strucutre of the site.
- **Wireframe** each page to organize the information.
  - wireframing resources:
     - [gomockingbird](https://gomockingbird.com/home)
     - [lovelycharts](https://lovelycharts.com)
- Use **contrast** (size, color, style) to create a visual hierarcy thats across your key message and helps users find what they are looking for.
- **Group** related information together to make it easier to understand.
   - grouping techniques:
     - proximity
     - closure
     - continuance
     - white space
     - color
     - borders
     
## Duckett: HTML & CSS, Chapter 1: Structure

<"opening tag" "attribute">Text</"closing tag"> *the whole thing is an **element***

## Duckett: HTML & CSS, Chapter 17 - HTML5 Layout

HTML5 discards <div> notation and uses descriptive notation to differentiate different types of elements.

> examples: <header> <section> <footer>
## Duckett: HTML & CSS, Chapter 8 - Extra Markup

To make a comment in HTML: `<!-- commented out text -->`

You can label elements by giving them an *id attribute* in the opening tag.  This becomes useful with a linked CSS file because can use that label to style that element differently than the rest of the page.

> example: `<p id="blah">Text, text, text</p>`

You can label several elements as a group with a *class attribute*

> example: `<p class="important">Text...</p>`

*block elements* appear to start on a new line in the brower window.

> examples: `<h1>`, `<p>`, `<ul>`, `<li>`

*inline elements* appear to continue on the same line.

> examples: `<a>`, `<b>`, `<em>`, `<img>`

Other fun elements: `<div`, `<span>`, `<iframe>`, `<meta>`
