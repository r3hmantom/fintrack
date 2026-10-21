# Raqza website

The landing page for Raqza, a private money tracker for Android.
Live at https://r3hmantom.github.io/fintrack/

Plain HTML and CSS, no build step. Screenshots are real captures from the app
(`integration_test/marketing_test.dart` in the app repo seeds demo data and
takes them on a phone).

## Branding assets

The mascot SVGs (`assets/mascot.svg`, `assets/mascot-animated.svg`, `assets/favicon.svg`) come from
`design/brand/raqza-mascot-v2.html`. The touch icon, `icon-192.png`, `icon-512.png` and the social
card `og.png` come from the app's own mascot painter:

```bash
flutter test tool/icons/generate_site_images_test.dart
```
