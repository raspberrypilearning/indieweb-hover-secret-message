<h2 class="c-project-heading--task">Hide the secret message</h2>

Make the secret message disappear so it can be revealed later with hover.

<h2 class="c-project-heading--explainer">Make this change</h2>

Stay in `style.css` and add this `.secret-message` rule underneath `.cover-note`. Setting the text `opacity` to `0` makes it invisible!

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 98
line_highlights: 100-111
---
}

.secret-message {
  margin: 18px 0 0;
  padding: 14px 16px;
  border: 3px solid var(--accent-hot);
  border-radius: 18px;
  background: rgba(255, 228, 90, 0.28);
  color: #9d004e;
  font-weight: 700;
  opacity: 0;
  transform: translateY(14px) scale(0.96);
  transition: opacity 0.25s ease, transform 0.25s ease;
}
--- /code ---

</div>

<div class="c-project-tip">

<h3>Tip</h3>

<p>Pick colours and styles you like by editing the values.</p>

<p>Small value changes can make the page feel really different!</p>

<p><a href="https://www.google.com/search?q=web+colour+picker" target="_blank" rel="noopener noreferrer">Open the Google web colour picker in a new tab</a> if you want help choosing colours.</p>

</div>

## Now run your code

The secret message should disappear, even though it is still in the HTML file.

<div class="c-project-output">
  <img src="images/step_6_output.png" alt="Expected project output after step 6 showing the secret message hidden from view.">
</div>
