# Academic website

This repository publishes the academic website at:

**https://hamza-elfadili.github.io**

## Modify the text

1. Open `index.html`.
2. Click the pencil icon (**Edit this file**).
3. Replace the text you want to change.
4. Click **Commit changes**.

The name, biography, research fields, and current research project are all in `index.html`.

## Modify the colors

1. Open `style.css`.
2. Click the pencil icon.
3. Change the color values at the top of the file:

```css
:root {
  --ink: #16262d;
  --paper: #f5f2ea;
  --accent: #9d5d3d;
}
```

- `--ink` controls the main text color.
- `--paper` controls the background.
- `--accent` controls the accent color.

## Add an email later

Add this line in `index.html` where you want the link to appear:

```html
<a href="mailto:your.address@ulaval.ca">Email</a>
```

## Add a CV later

1. Upload a file named `cv.pdf` to this repository.
2. Add this link in `index.html`:

```html
<a href="cv.pdf">CV</a>
```

## Add a working paper later

Upload the PDF to the repository and add a link in the Research section. Keep the label **Research in development** until a communicable draft exists.

Changes published to the `main` branch normally appear on the website after GitHub Pages finishes rebuilding.
