# Palette Pal

Paint by numbers from a photo, a camera overlay for tracing onto canvas, and a paint colour mixer.

- `www/index.html` is the whole app. Edit this file to change the app.
- `codemagic.yaml` builds the iPhone app and sends it to TestFlight.
- `assets/` holds the app icon and splash screen.
- The `ios` folder is created by Codemagic on each build, so it is not in the repo.

Before the first build, fill in `YOUR_CODEMAGIC_API_KEY_NAME` and `APP_STORE_APPLE_ID` in `codemagic.yaml`.
