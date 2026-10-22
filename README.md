# Mochi app backup

Complete source snapshot of the Mochi meditation and breathing app, including the latest typography, spacing, color and illustration refinements, email/password sign-up and login, preferred-name onboarding, mood journal, streak counter, AI companion server route, and iOS Xcode project.

## Restore

1. Download `mochi-github-backup.zip` from this repository and unzip it.
2. Open the extracted `mochi-github` folder. It contains the full web application source.
3. Follow its README to install dependencies, configure your own server-side environment, and apply the local database migrations.
4. The native iPhone project is in `mochi-github/ios/`. Its README explains the remaining TestFlight requirements and native build limitations.

## What is saved

The ZIP preserves all project subdirectories and source files. TypeScript and the production web build passed before this snapshot. Latest theme, typography, mood bubble and calendar-week changes were checked in the browser preview. The iOS project has not been uploaded to TestFlight.

API keys, passwords, local account databases, local history, dependency caches and generated build output are excluded. Configure a new server environment when restoring. No open-source license has been added; third-party notices remain included.

Archive SHA-256: `0420ee81f6ef7a3bf5a2832f08007e3762f3393567929ff8113c293215907254`

## Latest update

White background, black text and buttons, larger explore/profile text, larger weekday labels and mood bubbles, no empty-day captions, and Sunday–Saturday current-week mood history. The ZIP includes these latest source changes.
