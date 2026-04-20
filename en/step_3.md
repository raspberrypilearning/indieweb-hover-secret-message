<h2 class="c-project-heading--task">Style the box</h2>

You will turn the plain file box into something bright and bold.

### Step 1

Stay in `style.css` and add the `.secret-box` rule underneath the `body` rule.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 15
line_highlights: 17-29
---
}

.secret-box {
  width: min(360px, 100%);
  padding: 28px;
  border: 6px solid #20113a;
  border-radius: 24px;
  background:
    linear-gradient(180deg, rgba(255, 255, 255, 0.55), transparent 24%),
    #ffffff;
  box-shadow:
    0 0 0 8px #ff4cb0,
    0 18px 0 #20113a;
  text-align: center;
}
--- /code ---

</div>

### Step 2

Underneath `.secret-box`, add the `.box-label` rule to make the heading stand out.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 29
line_highlights: 31-37
---
}

.box-label {
  margin: 0;
  font-size: 2rem;
  font-weight: 900;
  text-transform: uppercase;
  text-shadow: 2px 2px 0 #8cf5ff;
}
--- /code ---

</div>

### Step 3

Underneath `.box-label`, add the `.box-note` rule so the text stays easy to read.

When you finish, your stylesheet should have the `body`, `.secret-box`, `.box-label`, and `.box-note` rules in that order.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 37
line_highlights: 39-43
---
}

.box-note {
  margin: 14px 0 0;
  font-size: 1rem;
  line-height: 1.5;
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

**Run your code:** The box should now look bright and bold, but the secret message should still be visible.

<div class="c-project-output">
  <img src="images/step_3_output.png" alt="Observed project output after this step.">
</div>
