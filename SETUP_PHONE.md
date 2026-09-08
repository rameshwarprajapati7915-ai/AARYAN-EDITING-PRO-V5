# Phone-only setup

The easiest no-PC route is GitHub Actions.

### Upload
Upload all project files to your GitHub repository. Do not upload only `index.html`.

### Build
Open **Actions** → **Build AARYAN EDITING APK** → **Run workflow**.

### Download
When the job is green, open the job summary and download:
`AARYAN-EDITING-V5-debug-apk`

### Install
Extract the downloaded ZIP and open `app-debug.apk`.

If Android blocks installation, use the system option that allows installation of apps from the browser/file manager you used to open the APK.

For Google Play publishing later, use a signed release AAB/APK and Play App Signing; the debug APK is for testing only.
