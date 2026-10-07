- At least one image (`<img>`) with `alt` text describing it
- **Your sections:** `padding`, `margin`, and a `border` or background color
  so each part of the recipe is clearly grouped
- **Images:** a size that fits nicely on the page
- **Fonts:** At least one custom font from [Google Fonts](https://fonts.google.com/).
- **The typography triangle:** Readable text comes from balancing three things:
  - `font-size` — how big the letters are
  - `line-height` — how much space is between the lines
  - `max-width` — how long each line can get
- **Selectors:** Element selectors (`h2 { ... }`), at least one class
  (`.tip { ... }`) that styles _some_ elements differently from others of the
  same type, and at least one descendant selector (`.tip p { ... }`) that
  styles elements only when they are inside something else.
- **The box model:** `padding`, `margin`, and `border` to group related
  content and give your page room to breathe.
- **Organization:** Your `styles.css` is organized into sections with
  comments explaining what each part styles.

**No layout tools yet!** For this project, your page should flow from top to
bottom. Do not use `display: flex`, `display: grid`, or `position`.
We'll get to those soon. That means you generally won't be able to put items
side-by-side in this project (unless you use `float`).

### Honors Components (in addition to main components):

- **Advanced typography:** pair a heading font with a body font, and use at
  least three of these to fine-tune your text:
  - `font-weight` (using more than one weight of a font)
  - `letter-spacing`
  - `text-transform` (for example, all-caps headings)
  - `font-variant: small-caps`
  - `font-variant-numeric: diagonal-fractions` (makes 1/2 look like ½)
  - `text-align` and `text-indent`
- Customize list markers (bullets and numbers) using `list-style` or `::marker`.
- Use a pseudo-element (`::before` or `::after`) to add a custom marker to at least one item.
- Use a "recipe info" box (prep time, cook time, servings — or the
  metaphorical equivalent) styled with a class.

## Resources

- [Mr. H's YouTube Tutorials](https://www.youtube.com/playlist?list=PLMEapm-6E2Mg) 
- [Validity Checker](https://validator.w3.org/nu/) _(ignore character encoding warnings)_
- [W3Schools CSS Tutorial](https://www.w3schools.com/css/default.asp)
- [MDN: CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Basic_selectors)
- [MDN: The Box Model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)
- [CSS-Tricks: The Equilateral Triangle of a Perfect Paragraph](https://css-tricks.com/equilateral-triangle-perfect-paragraph/) — the typography triangle

### Color & Font Resources

- [Coolors](https://coolors.co/) — generate color schemes, or pull one from an image
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) — make sure your text is readable
- [Google Fonts](https://fonts.google.com/) — pick a font and copy its `<link>` tag into your `<head>`

### Honors Resources

- [CSS Custom Properties (Variables) - W3Schools](https://www.w3schools.com/css/css3_variables.asp)
- [Styling Lists - MDN](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Text_styling/Styling_lists)
- [The `::marker` pseudo-element - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker)
- [The `::before` and `::after` pseudo-elements - W3Schools](https://www.w3schools.com/css/css_pseudo_elements.asp)

# Recipe Project Rubric

Grading will happen in two phases:

1. You will get a "Digital Creation" grade based on the quality of your published website.

2. You will get a "Content" grade based on your in-class write-up explaining your code and design decisions.

## Published Website Rubric

Starred items (\*) are for honors students.

<table border="1">
  <tr>
    <th>Criteria</th>
    <th>1 - Beginning</th>
    <th>2 - Developing</th>
    <th>3 - Proficient</th>
    <th>4 - Mastery</th>
  </tr>
  <tr>
    <th>CSS</th>
    <td><!-- css | 1 --></td>
    <td><!-- css | 2 --></td>
    <td><ul>
          <li>CSS is used to customize:
            <ul>
              <li>Fonts</li>
              <li>Colors</li>
              <li>Padding and margins</li>
            </ul>
          </li>
        </ul></td>
    <td><ul>
          <li>Uses a variety of rules: the core properties (<code>font-size</code>, <code>line-height</code>, <code>width</code>, <code>padding</code>, <code>color</code>, <code>background-color</code>) plus properties looked up and learned on your own (e.g. <code>box-shadow</code>, <code>text-shadow</code>).</li>
          <li>Human-written comments say where you learned each new property (e.g. <code>/* box-shadow: learned from MDN */</code>).</li>
          <li>Uses CSS variables and advanced typography settings.*</li>
        </ul></td>
  </tr>
  <tr>
    <th>HTML</th>
    <td><!-- html | 1 --></td>
    <td><!-- html | 2 --></td>
    <td><ul>
          <li>The recipe includes:
            <ul>
              <li>Headings</li>
              <li>Sections (such as <code>header</code>, <code>main</code>, <code>section</code>, <code>div</code>, <code>footer</code>)</li>
              <li>Lists</li>
            </ul>
          </li>
        </ul></td>
    <td><ul>
          <li>Nuanced formatting, e.g. the amount, unit, and ingredient in each ingredient are marked up and styled distinctly.</li>
          <li>Includes a "recipe info" box styled with a class.*</li>
        </ul></td>
  </tr>
  <tr>
    <th>Design</th>
    <td><!-- design | 1 --></td>
    <td><!-- design | 2 --></td>
    <td><ul>
          <li>No accessibility problems with color contrast.</li>
          <li>Fonts are readable.</li>
          <li>Uses a custom font.</li>
          <li>Nothing crashes into an edge.</li>
        </ul></td>
    <td><ul>
          <li>Color scheme is thematic, attractive, and fits the recipe.</li>
          <li>Typography is thoughtfully laid out (typography triangle respected).</li>
          <li>Padding and margins are tweaked for optimal rhythm.</li>
        </ul></td>
  </tr>
  <tr>
    <th>Process</th>
    <td><!-- process | 1 --></td>
    <td><!-- process | 2 --></td>
    <td><ul>
          <li>The site passes validation with minor issues.</li>
        </ul></td>
    <td><ul>
          <li>CSS is organized into sections with comments.</li>
          <li>A steady log of commit messages shows progress over time.</li>
        </ul></td>
  </tr>
</table>

## In-Class Write-Up Rubric (Content Strand)

This will be an assessment based on an in-class write-up you will do with questions you will not know ahead of time.

<table border="1">
  <tr>
    <th>Criteria</th>
    <th>1 - Beginning</th>
    <th>2 - Developing</th>
    <th>3 - Proficient</th>
    <th>4 - Mastery</th>
  </tr>
  <tr>
    <th>CSS Properties & Values</th>
    <td><!-- properties | 1 --></td>
    <td><!-- properties | 2 --></td>
    <td><ul><li>Identifies the selector, property, and value in a CSS rule, and explains what common properties (such as <code>color</code>, <code>font-size</code>, <code>padding</code>, <code>margin</code>) do.</li></ul></td>
    <td><ul>
          <li>Predicts how changing a value will change the page, and chooses properties and values to create a described effect.</li>
        </ul></td>
  </tr>
  <tr>
    <th>Selectors</th>
    <td><!-- selectors | 1 --></td>
    <td><!-- selectors | 2 --></td>
    <td><ul><li>Explains which elements an element selector (<code>li</code>) and a class selector (<code>.tip</code>) will style.</li></ul></td>
    <td><ul>
          <li>Predicts which elements a descendant (nested) selector like <code>.tip p</code> will style, and writes a selector to target a described element.</li>
        </ul></td>
  </tr>
</table>
