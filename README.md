<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/33e41f36-1eff-4afc-95fc-0413bca93001

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`

## Android APK with GitHub Actions

1. Upload this project to a GitHub repository.
2. Open the repository on GitHub.
3. Go to `Actions`.
4. Open `Android APK`.
5. Click `Run workflow`, or push a new change to `main` / `master`.
6. When the run finishes, download the `Pati-Petshop-debug-apk` artifact.

The APK file will be inside the downloaded artifact as:

`app-debug.apk`
