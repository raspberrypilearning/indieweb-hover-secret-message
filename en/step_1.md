<h2 class="c-project-heading--task">Add the leaked file header</h2>

Add the visible header inside `<main class="secret-box">` so the page stops looking empty.

<h2 class="c-project-heading--explainer">Make this change</h2>

## Step 1
Run the code to see the unstyled page.

## Step 2
The starter file has an empty `<main>` element, so add the eyebrow, the main heading, and the mood line inside it:

These tags create the visible file header. The class names give you hooks to style each part later in `style.css`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 10-12
---
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>chatlog_FINAL-final_REAL.txt</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <main class="secret-box">
      <p class="eyebrow">Recovered hover artefact // cached at 2:17am</p>
      <h1>chatlog_FINAL-final_REAL.txt</h1>
      <p class="status">mood: blocked by the glitter cursor</p>
    </main>
  </body>
</html>
--- /code ---

</div>

## Now run your code

You should see the leaked file header inside the box instead of an empty page section.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Expected project output after step 1 showing the leaked file header inside the box.">
</div>
