# BASE WORLD MALAWI — Starter Foundation

**Motto:** From Malawi to the World.  
**Principle:** Humanity Before Technology.

This repository is the initial, honest-to-test foundation for BASE WORLD MALAWI.
It contains an Android prototype for the BASE GUARD flagship project and a GitHub
Actions workflow that attempts to build a debug APK.

## Important prototype notice
The current app is a UI prototype only. Its SOS button does **not** contact
emergency services, transmit location, or guarantee rescue. Do not rely on it
during an emergency. Real emergency workflows require verified local contacts,
user consent, privacy/security review, and field testing.

## Project layout
- `app/` — Android application prototype.
- `.github/workflows/android-apk.yml` — automatic debug APK build.
- `docs/` — founding charter, architecture, roadmap and safety requirements.

## Build
Open this repository in Android Studio, or push it to GitHub and run
**Actions → Android APK → Run workflow**. On success, download the
`base-guard-debug-apk` artifact from the workflow run.

## First development priorities
1. Confirm the real emergency use cases and verified response partners.
2. Design consent-based location sharing and secure data handling.
3. Implement and test features in small stages.
4. Never advertise an untested feature as an operational rescue service.
