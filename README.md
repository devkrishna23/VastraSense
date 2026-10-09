# Clothes labelling (VastraSense)

A small static page where Harsh and Somil each label 300 different real phone photos of clothes: the **type** of the
main garment and its **colour**, answered blind (no hints). These labels help train VastraSense's on-device model.
It runs entirely in the browser, on a laptop or an Android phone.

## For Harsh and Somil

1. Open the page link and tap your name. You get your own 300 photos.
2. For each photo: choose the category and type, then the main colour (swatches or the colour wheel), then
   **Save & next**. Use **Ambiguous photo** when you cannot tell.
3. Your answers are kept on your device as you go (do not use a private/incognito tab). When you stop, press
   **Send my labels** and send the file to Krishna. You can continue later on the same device and browser.

## Contents

- `index.html`: the whole page (no server, no build step)
- `photos/`: 600 photos from Alexey Grigorev's clothing dataset, released under CC0 (public domain)
- `people.json`, `items_harsh.json`, `items_somil.json`: who gets which photos. `taxonomy.json`: allowed types and colours.

## Publishing on GitHub Pages

Upload every file in this folder (including the empty `.nojekyll`) to a public repository, then go to
**Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
