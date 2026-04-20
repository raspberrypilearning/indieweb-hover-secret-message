<h2 class="c-project-heading--task">Make the box appear</h2>

You will give the file box a plain shape so it shows up on the page, even though it still looks a bit dull.

Stay in `style.css` and add a simple `.secret-box` rule underneath the `body` rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 15
line_highlights: 17-22
---
}

.secret-box {
  width: min(360px, 100%);
  padding: 28px;
  border: 2px dashed #20113a;
  background: rgba(255, 255, 255, 0.4);
  text-align: center;
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

**Run your code:** You should now see the file box appear on the page, but it should still look quite plain.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Observed project output after this step.">
</div>
