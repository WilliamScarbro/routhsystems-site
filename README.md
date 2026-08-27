# Routh Systems -- website

The static site for routhsystems.com. One self-contained file: `index.html`.
No build step, no dependencies. Fonts are requested from Google Fonts;
everything else is inline.

Deployed via Porkbun static hosting, which publishes from this repository.

To preview locally:

```sh
python3 -m http.server 8000
```

Canonical source and the design notes live in the private repository under
`site/`. Edit there, then publish here.
