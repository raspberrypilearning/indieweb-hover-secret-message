<h2 class="c-project-heading--task">Style the cover story</h2>

Give the cover story its own suspicious sticker look so it stands apart from the rest of the text.

<h2 class="c-project-heading--explainer">Make this change</h2>

Stay in `style.css` and add this `.cover-note` rule underneath the `p` rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 88
line_highlights: 90-98
---
}

.cover-note {
  margin-top: 18px;
  padding: 14px 16px;
  border: 3px dashed var(--ink);
  border-radius: 18px;
  background: rgba(255, 255, 255, 0.62);
  box-shadow: inset 0 0 0 2px rgba(255, 255, 255, 0.48);
  transform: rotate(-1deg);
}
--- /code ---

</div>

## Now run your code

The cover story should now look like a suspicious label stuck onto the file.

<div class="c-project-output">
  <img src="images/step_5_output.png" alt="Expected project output after step 5 showing the cover story styled like a suspicious label.">
</div>
