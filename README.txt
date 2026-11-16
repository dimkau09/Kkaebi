KKAEBI: LEARN KOREAN - installable web app
=========================================

This folder is a complete web app. Put it on any free static web host with
HTTPS and it can be installed on Windows, Android, iPhone and iPad. It works
offline after the first visit.

A. Host it for free on GitHub Pages (about 10 minutes, one time)
  1. Create a free account at github.com and sign in.
  2. Top right: "+" > New repository. Name it "kkaebi". Set it to Public.
     Click Create repository.
  3. On the new repository page choose "uploading an existing file". Drag in
     every file from this folder (index.html, sw.js, manifest.webmanifest and
     the three .png files). Click Commit changes.
  4. Open Settings > Pages. Under "Build and deployment" set Source to
     "Deploy from a branch", pick the "main" branch, and Save.
  5. After a few minutes (up to 10) your app is live at
     https://YOUR-USERNAME.github.io/kkaebi/
  Any other static host works the same way: upload the files, open the URL.

B. Install it
  Android (Chrome):  open the URL, tap "Install" in the bar Kkaebi shows, or
                     menu (three dots) > Install app / Add to Home screen.
  iPhone or iPad:    open the URL in Safari, tap Share, then
                     "Add to Home Screen".
  Windows (Edge or Chrome): open the URL, click the install icon in the
                     address bar, or menu > Apps > Install this site as an app.

C. Good to know
  - Progress is saved on each device separately. To move it, use
    Settings > Backup > Export on one device and Import on the other.
  - Voice uses the Korean text-to-speech voice of your device.
  - Free conversation with Claude, AI stories and "Why was this wrong?" only
    exist in the Claude version. Scripted calls work everywhere.
  - To update the app later, upload the new index.html over the old one and
    raise the number in 'nuri-v7' on line 2 of sw.js.

D. Updating from the earlier "Nuri" version
  Upload all files from this folder over the old ones in the SAME repository
  and keep using the same address. Your progress on each device is kept.
  On a phone, the home-screen icon and name refresh after you remove the old
  icon and add the app to the home screen again.
