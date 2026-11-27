# Rozmee Apps

Source for [rozmeeapps.github.io/rozmeeapps](https://rozmeeapps.github.io/rozmeeapps/), the website for Rozmee's Android apps.

## Phone Widgets

- [App page](https://rozmeeapps.github.io/rozmeeapps/): home screen widgets for Android
- [Privacy policy](https://rozmeeapps.github.io/rozmeeapps/phone-widgets-privacy-policy.html): the URL used in the app and on the Google Play listing. Keep it stable.

## MotionCalm

- [App page](https://rozmeeapps.github.io/rozmeeapps/motioncalm.html): vehicle motion cues for passengers
- [Privacy policy](https://rozmeeapps.github.io/rozmeeapps/motioncalm-privacy-policy.html): used in the app and on the Google Play listing. Keep it stable.
- [Terms & Conditions](https://rozmeeapps.github.io/rozmeeapps/motioncalm-terms.html): used in the app. Keep it stable.
- Support: rozmee.dev@gmail.com

## Hidden Settings

- [Privacy policy](https://rozmeeapps.github.io/rozmeeapps/hidden-settings-privacy-policy.html): used in the app and on the Google Play listing. Keep it stable.
- [Terms & Conditions](https://rozmeeapps.github.io/rozmeeapps/hidden-settings-terms.html): used in the app. Keep it stable.
- Support: rozmee.dev@gmail.com

## Structure

- `index.html`: Phone Widgets landing page (SEO metadata, JSON-LD)
- `phone-widgets-privacy-policy.html`: Phone Widgets privacy policy
- `motioncalm.html`, `motioncalm-privacy-policy.html`, `motioncalm-terms.html`: MotionCalm pages
- `assets/phone-widgets/`: app icon and Outfit fonts (SIL OFL, see `OFL.txt`); the fonts are shared with MotionCalm
- `assets/motioncalm/`: MotionCalm icon (SVG) and shared stylesheet (light and dark themes)
- `hidden-settings-privacy-policy.html`, `hidden-settings-terms.html`: Hidden Settings pages
- `assets/hidden-settings/`: Hidden Settings icon (SVG) and stylesheet (the MotionCalm stylesheet in the app's blue)
- `robots.txt`, `sitemap.xml`: search engine discovery
- `404.html`: custom error page

Plain HTML/CSS on GitHub Pages (deploy from `main`, root). No build step is needed.

## Local preview

```sh
python3 -m http.server 8000
```

## Contact

- Phone Widgets: rozmee.apps@gmail.com
- MotionCalm: rozmee.dev@gmail.com
- Hidden Settings: rozmee.dev@gmail.com
