PIXELFLIX ANDROID APP — ONLINE APK BUILD

This is an Android Studio project configured to build an installable debug APK using GitHub Actions.
It is not itself an APK.

BUILD ON GITHUB (can be done from your phone browser):
1. Sign in or create a GitHub account at https://github.com/.
2. Create a new repository. Name it PixelFlixAndroid. Public or private is your choice.
3. On the new repository page, choose Add file > Upload files.
4. Extract this ZIP first, then upload the CONTENTS of the PixelFlixAndroid folder (including the hidden .github folder and its workflows/build-apk.yml file). If your phone's file picker hides dot-folders, use GitHub's web upload from a computer or a file manager that shows hidden files.
5. Commit the uploaded files to the main branch.
6. Open the repository's Actions tab. Select “Build PixelFlix APK” and press “Run workflow” if it has not started automatically.
7. Wait for the workflow to finish successfully. Open that run and find Artifacts; download “PixelFlix-APK”.
8. Extract the downloaded artifact ZIP. Tap app-debug.apk on your Android phone and allow your browser/file manager to install unknown apps if Android asks.

The build workflow uses GitHub-hosted runners, Java 17, Gradle 8.9, and the Android Gradle Plugin 8.7.3.

APP NOTES:
- The app is a WebView wrapper for https://www.pixelflix.cc/.
- It does not host, download, or own the site's content.
- Site availability, playback, login, embeds, and third-party behavior are controlled by the website.
- Only install if you trust the website. Review its privacy and security before entering credentials or payment details.
- This debug APK is suitable for personal testing; it is not a Play Store release build.
