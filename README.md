# <img src="https://github.com/LF-digitala-kanaler/favicon/blob/master/icon.svg" width="24"> Länsförsäkringar Favicon

Updated 2022 based on [research by Evil Martians](https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs).

## Implementation

1. Copy the assets to a public directory (preferably the root).
2. Add the below links to your document.
3. Optinally, define a [name and short name](https://developer.chrome.com/docs/extensions/mv2/manifest/name/) in the webmanifest file.

```html
<head>
  <!-- ... -->
  <link rel="icon" href="/favicon.ico" sizes="any">
  <link rel="icon" href="/icon.svg" type="image/svg+xml">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  <link rel="manifest" href="/manifest.webmanifest">
<head>
```
