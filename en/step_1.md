<h2 class="c-project-heading--task">Add the secret message</h2>

You will turn the plain file box into a hover target with one hidden message inside it.

Open `index.html` and add one extra paragraph for the secret message inside the box.

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
      <p class="box-label">Routine File</p>
      <p class="box-note">This file claims it contains only receipts and no rebellious field notes.</p>
      <!-- Add one hidden message inside the same box. -->
      <p class="secret-message">Agent memo: the pigeons joined the resistance, and frankly they made fair points.</p>
    </main>
  </body>
</html>
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

You should see the new secret-agent note sitting inside the box for now.

<div class="c-project-output">
  <img src="images/step_1_output.png" alt="Observed project output after this step.">
</div>
