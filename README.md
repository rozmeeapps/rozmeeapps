# Rozmee Apps

Source for [rozmeeapps.github.io/rozmeeapps](https://rozmeeapps.github.io/rozmeeapps/), the website for Rozmee's Android apps.

## Phone Widgets

- [App page](https://rozmeeapps.github.io/rozmeeapps/): home screen widgets for Android
- [Privacy policy](https://rozmeeapps.github.io/rozmeeapps/phone-widgets-privacy-policy.html): the URL used in the app and on the Google Play listing. Keep it stable.

## Structure

- `index.html`: Phone Widgets landing page (SEO metadata, JSON-LD)
- `phone-widgets-privacy-policy.html`: privacy policy
- `assets/phone-widgets/`: app icon and Outfit fonts (SIL OFL, see `OFL.txt`)
- `robots.txt`, `sitemap.xml`: search engine discovery
- `404.html`: custom error page

Plain HTML/CSS on GitHub Pages (deploy from `main`, root). No build step is needed.

## Local preview

```sh
python3 -m http.server 8000
```

## Contact

rozmee.apps@gmail.com
