# Länsförsäkringar Favicon
Updated 2022, based on [research by Evil Martians](source).

## Implementation
Copy the assets to a public directory (preferably the root) and link them in as
done below.

```html
<head>
  <!-- ... -->
  <link rel="icon" href="/favicon.ico" sizes="any">
  <link rel="icon" href="/icon.svg" type="image/svg+xml">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  <link rel="manifest" href="/manifest.webmanifest">
<head>
```

[source]: https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs
