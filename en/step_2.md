<h2 class="c-project-heading--task">Add the page background</h2>

You will centre the page on a loud background so the box has room to feel suspicious.

Open `style.css` and start by adding these `*` and `body` rules.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 1-15
---
/* Style one innocent-looking box and reveal its secret on hover. */
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  min-height: 100vh;
  display: grid;
  place-items: center;
  padding: 24px;
  font-family: "Trebuchet MS", Verdana, sans-serif;
  color: #20113a;
  background: linear-gradient(180deg, #fff3a6, #ff9fda 55%, #8cf5ff 100%);
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

**Run your code:** You should now see the page sitting on a bright background, even though the box still looks plain.

<div class="c-project-output">
  <img src="images/step_2_output.png" alt="Observed project output after this step.">
</div>
