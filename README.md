# css-toggle
A minimalist CSS-only toggle for your websites.

## Installation

Just copy the `toggle.css` file into your project and add the following line of HTML into your `<head>` tag:

```html
<link rel="stylesheet" href="./toggle.css" />
```

## Usage

Just add these two elements anywhere in your HTML:

```html
<input type="checkbox" id="your_unique_id" class=check" />
<label for="your_unique_id" class="toggle"></label>
```

You can add an infinite number of toggles as long as they all have differents id/for attributes.

## Use the value in your backend

Just add a `name` attribute to your `input` tags and handle them as regular checkboxes in your backend.
