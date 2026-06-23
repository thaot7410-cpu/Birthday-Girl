# Birthday Countdown Daily Gift Website

This version is ready for GitHub Pages.

## How to add your photo

1. Open the `assets` folder.
2. Upload your photo into that folder.
3. Rename the photo exactly to:

```text
IMG_1724.jpg
```

The website already has this line in `index.html`:

```html
<img src="assets/IMG_1724.jpg" alt="Her photo" class="main-photo" onerror="this.style.display='none'">
```

If your photo has a different name, change the `src` to match it exactly. Example:

```html
<img src="assets/her-photo.png" alt="Her photo" class="main-photo" onerror="this.style.display='none'">
```

## How to publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and the `assets` folder.
3. Go to Settings, then Pages.
4. Under Branch, choose `main`, then `/root`.
5. Click Save.
6. Wait a minute, then open the GitHub Pages link.

Important: GitHub Pages needs the homepage file to be named `index.html`.
