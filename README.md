# Yojet Sharma personal website

Plain HTML, CSS and JavaScript. There is nothing to install or build.

- `index.html`: the whole site (text, styles, code)
- `gallery.js`: the list of gallery photos
- `images/`: the photo files

## View it on your computer
Double-click `index.html`. It opens in any browser.

## Add a photo
1. Upload it to `images/`.
2. Add a line to `gallery.js`, for example:
   `{ file: "my-neurons.jpg", caption: "Neurons imaged at NCBS" },`
3. On GitHub, commit the change. The live site updates within a few minutes.

## Change text
Open `index.html` in any text editor (on GitHub, use the pencil icon), search for the words, edit, save.

## Publish on GitHub Pages
1. Create a public repository named `<your-username>.github.io`.
2. Upload everything in this folder, keeping the `images` folder.
3. In Settings > Pages, set the source to "Deploy from a branch", then `main` and `/ (root)`.
4. The site appears at `https://<your-username>.github.io`.

## If you ever move it
Any static host works (Netlify, Cloudflare Pages, a university web space). Upload the same files.
