# Lull for Android

A thin Android app that opens Lull full screen. The address is `LULL_URL` in `app/build.gradle`.

## Get the APK without installing anything
1. Create a GitHub repo and push this folder to the `main` branch.
2. Open the repo's **Actions** tab. The "Build APK" run takes a few minutes.
3. When it is green, open **Releases > Lull (latest build)** and download `app-debug.apk`. That page is the link you can share.
4. On the phone, open the file and allow "install unknown apps" for the browser when asked.

## Notes
- This is a debug-signed build, fine for sharing and testing. Google Play needs a release build signed with your own key.
- Lull's data is only readable by people signed in to claude.ai, so the app asks for sign-in and only works for people with an account there. A public app needs Lull moved to its own backend (see Lull's docs/SUBSCRIPTIONS.md).
- Untested: the build could not be run in the environment this was written in.
