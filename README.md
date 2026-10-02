# Brightslate Exterior Cleaning

Animated one-page website for a roof and exterior cleaning business (Louth, Meath and north Dublin). The business name, prices, reviews and phone number are placeholders.

## What's in it

- Squeegee intro that wipes a dirty screen clean, with a % counter
- Hero photo where visitors wash the moss off a real roof
- Gallery of real job photos, each wiped clean by a squeegee as it scrolls into view
- Before/after squeegee slider (roof and driveway)
- Scroll-driven tour of a roof clean in four steps
- Instant price calculator and a two-step booking form (demo only, nothing is sent)
- Eircode area checker with an animated map, reviews and FAQ

## Run it

It's a single static page. Open `index.html` through any web server, for example:

```
python3 -m http.server 8000
```

then visit http://localhost:8000. Opening the file directly from disk mostly works, but the "wash the moss" photo needs a server so the browser lets the page read the image.

## Files

- `index.html`: the whole site (HTML, CSS and JavaScript)
- `img/`: job photos as WebP
