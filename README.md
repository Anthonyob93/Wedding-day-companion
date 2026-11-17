# Wedding Day

A shoot-day companion app for Android, for weddings, family sessions and events: timeline with alerts, group lists, must-have shots, kit check, contacts, venues with photos, weather, sunset / golden hour, questionnaire import, plan PDFs, calendar links and automatic backups. Everything is stored on the phone; use **Backup** in the app to keep a copy.

## Install or update

On your Android phone, open:

**https://github.com/Anthonyob93/wedding-day-companion/releases/latest/download/WeddingDay.apk**

Open the downloaded file and tap **Install**. The first time, Android asks you to allow installs from your browser. Updates install the same way, over the top, and keep your data.

## How it's built

`www/index.html` is the whole app. Every push to `main` builds a signed APK with GitHub Actions (Capacitor 6) and publishes it as a release.
