<h2 class="c-project-heading--task">Give it terminally bad taste</h2>

Open `style.css` and edit the values inside `:root`. These custom properties control the page background, the panel colours, the accent colours, the border size, the font, and the file width.

<div class="c-project-tip">

<h3>Tip</h3>

<p>Pick colours that feel like a cursed profile upload, a fake warning sticker, or a leaked file that absolutely should not exist.</p>

<p>Small value changes can make the page feel more sugary, more dramatic, or more chaotic.</p>

<p><a href="https://www.google.com/search?q=web+colour+picker" target="_blank" rel="noopener noreferrer">Open the Google web colour picker in a new tab</a> if you want help choosing colours.</p>

</div>

These custom properties store the main colours and sizes for the page. Changing them updates lots of the design without rewriting every CSS rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 2-13
---
/* Change these values to give the leaked file terminally bad taste. */
:root {
  --page-bg: #120014;
  --ink: #26001b;
  --panel-bg: #ffd8f2;
  --accent: #7eeeff;
  --accent-hot: #ff73c6;
  --accent-warning: #ffe45a;
  --shadow-color: #170011;
  --border-size: 5px;
  --corner-size: 18px;
  --body-font: Verdana, Geneva, sans-serif;
  --box-width: 35rem;
}
--- /code ---

</div>

## Now run your code

The page should still show the same text, but the colours and the overall mood should feel much more cursed.

<div class="c-project-output">
  <img src="images/step_4_output.png" alt="Expected project output after step 4 showing darker colours and louder leaked-file styling.">
</div>
