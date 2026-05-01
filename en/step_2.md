<h2 class="c-project-heading--task">Add the fake cover story</h2>

Add one cover-note paragraph underneath the mood line so the file pretends to be normal. When the user hovers over this text, more words will appear beneath. 

<h2 class="c-project-heading--explainer">Make this change</h2>

Put the new paragraph inside `<main class="secret-box">`, underneath `<p class="status">`. It can say anything you like.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 9
line_highlights: 13
---
    <main class="secret-box">
      <p class="eyebrow">Recovered hover artefact // cached at 2:17am</p>
      <h1>chatlog_FINAL-final_REAL.txt</h1>
      <p class="status">mood: blocked by the glitter cursor</p>
      <p class="cover-note">Hover over this file if you enjoy fake evidence and catastrophic profile decisions.</p>
    </main>
--- /code ---

</div>

## Now run your code

You should see the extra cover story paragraph underneath the mood line.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Expected project output after step 2 showing the leaked file header and the fake cover story paragraph.">
</div>
