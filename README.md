# Clothes labelling (VastraSense)

A small static page for labelling 300 real phone photos of clothes: the **type** of the main garment and its
**colour**, answered blind (no hints). It runs entirely in the browser, on a laptop or an Android phone.

## For friends

1. Open the page link and type your name.
2. For each photo: choose the category and type, then the main colour (swatches or the colour wheel), then
   **Save & next**. Use **Ambiguous photo** when you cannot tell.
3. Your answers are kept on your device as you go. When you stop, press **Send my labels** and send the file to Krishna.
   You can stop and continue later on the same device and browser.

## Contents

- `index.html`: the whole page (no server, no build step)
- `photos/`: the 300 photos, named by their test position. They come from Alexey Grigorev's clothing dataset,
  released under CC0 (public domain).
- `items.json`: the photo order. `taxonomy.json`: the allowed types and colours.

## Publishing on GitHub Pages

Create a new public repository, upload every file in this folder (including the empty `.nojekyll`), then go to
**Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save. The page appears at
`https://<your-user>.github.io/<repository>/` after a minute or two.
