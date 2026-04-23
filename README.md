# heyvirgil

A static personal site styled as a 1990s fan page — dark background, flickering torches, Gothic blackletter, and lyrical prose.

## Structure

```
index.html          homepage with nav tiles
pages/
  the-crossing.html full text page
  threshold.html    stub
  the-field.html    stub
  letters.html      stub
```

## Stack

Plain HTML and CSS. No build step, no dependencies, no JavaScript frameworks. The Google Fonts import (`UnifrakturMaguntia`) is the only external request.

## Adding a page

1. Copy an existing page in `pages/` as a starting point.
2. Replace the content inside `.body-text`.
3. Add a nav tile in `index.html` pointing to the new file.

## Running locally

Open `index.html` directly in a browser, or serve the directory with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```
