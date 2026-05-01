<h2 class="c-project-heading--task">Add the hidden note</h2>

Add one more paragraph underneath the cover story. This is the leaked note that will disappear and reappear later.

<h2 class="c-project-heading--explainer">Make this change</h2>

Add the new paragraph inside `<main class="secret-box">`, underneath `<p class="cover-note">`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 10
line_highlights: 16
---
    <main class="secret-box">
      <p class="eyebrow">Recovered hover artefact // cached at 2:17am</p>
      <h1>chatlog_FINAL-final_REAL.txt</h1>
      <p class="status">mood: blocked by the glitter cursor</p>
      <p class="cover-note">Hover over this file if you enjoy fake evidence and catastrophic profile decisions.</p>
      <p class="secret-message">I swear there was something here before, no cap on god bro.</p>
    </main>
--- /code ---

</div>

## Now run your code

You should see the cover story and the leaked note together for now.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Expected project output after step 3 showing the cover story and the leaked note both visible inside the file box.">
</div>
