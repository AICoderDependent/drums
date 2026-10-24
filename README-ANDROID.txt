DRUM TRAINER - how to put it online and install it on the tablet

FILES (7). Upload ALL of them to the top folder of your GitHub repository "drums":
  index.html
  manifest.webmanifest
  sw.js
  icon-192.png
  icon-512.png
  icon-512-maskable.png
  apple-touch-icon.png

UPLOAD
1. Open https://github.com/AICoderDependent/drums
2. Tap Add file, then Upload files.
3. Choose the 7 files. If GitHub asks, replace the old ones.
4. Tap Commit changes.
5. (Optional) Open the old file drum-trainer.html and delete it, so you only have one app page.
6. Wait one to two minutes.

OPEN AND INSTALL ON THE TABLET
1. In Chrome open https://aicoderdependent.github.io/drums/
2. Tap the three-dot menu.
3. Tap "Install app" (or "Install and create shortcut", then "Install").
4. Open the app from the new icon on the home screen. It opens without the browser bars.
If the menu only says "Add to Home screen", close Chrome fully, open the address again,
wait 10 seconds, and look at the menu again.

CONNECT THE KIT
1. Connect the kit to the tablet with the USB cable and switch the kit on.
2. Open the app and allow the MIDI question.
3. Tap the button at the top (it says Check my kit, or the kit name).
4. Hit pads and look at the messages. Press the test buttons. You should hear the kit.

UPDATE LATER
Replace index.html and sw.js in the repository. Before you upload sw.js, change the number in
the line   const CACHE = 'drum-trainer-v1';   to v2, v3 ... Then close and open the app again.

This app uses its own cache name (drum-trainer-...), so it does not touch the piano app.
