[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/linhy24/darkmode-switch/main/LICENSE)

# Darkmode switch
🌗
Make your webpage adapt to your system theme preference and manually adjustable through a toggle.

- The main goal is to make your webpage auto adjust its theme.
- Opt out from following system theme preference to adopt light theme.
- Use LocalStorage to store user preference.

## Setup
Make sure you include Bootstrap in your code.

- Code for adding a toggle (Bootstrap 5.0+):
```html
<div class="form-check form-switch">
    <label class="custom-control-label" for="toggle">Follow System</label>
    <input type="checkbox" class="form-check-input" id="toggle">
</div>
```

- Load darkmode CSS file:
```html
<link title="dark" rel="stylesheet" href="./darkmode.css" type="text/css">
```

- Load JavaScript file:
```html
<script src="./darkmode.js"></script>
```

## Demo
[Darkmode-swicth](https://linhy24.github.io/darkmode-switch)

