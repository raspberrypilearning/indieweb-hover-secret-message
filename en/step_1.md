<h2 class="c-project-heading--task">Add the secret note</h2>

You will add one hidden note inside the box.

Open `index.html` and add one more paragraph for the secret note inside the box.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 12-14
---
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Indieweb Hover Secret Message</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <main class="secret-box">
      <p class="box-label">File Box</p>
      <p class="box-note">This box says it only has boring papers.</p>
      <!-- Add one hidden note inside the same box. -->
      <p class="secret-message">Secret note: the toy dinosaur knows the password.</p>
    </main>
  </body>
</html>
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

You should see the new secret note inside the box for now.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Observed project output after this step.">
</div>
