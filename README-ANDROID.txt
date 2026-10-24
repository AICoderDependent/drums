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

PLAY ALONG WITH A YOUTUBE VIDEO (needs the internet)
1. Tap Videos at the top. Paste a YouTube link and tap Add video. The app remembers it.
2. Press play on the video. Tap "Tap tempo" in time with the music 8 times, or type the BPM.
3. At the first beat of a bar tap "Bar 1 starts here". Use the 10 ms buttons and the Click to line it up.
4. Choose a groove. Choose a different groove at the start of the chorus.
5. Slow the video down with the speed slider. Use Set A, Set B and Loop A to B for a hard part.
Live recordings that change speed will drift. Studio recordings work best.

HEAR THE VIDEO THROUGH THE KIT
The video plays on the tablet. To hear it from the kit use the tablet sound output (volume panel, Media output)
and choose the kit (USB audio), or use a 3.5 mm cable from the tablet to the kit's Audio Input.

LANES AND MUTE
Tap a lane name under Lanes: filled dot = play it, half dot = guide only, empty dot = off (hidden and silent).
"Song drums: muted" silences the groove the app plays on the kit.

UPDATE LATER
Replace index.html and sw.js in the repository. Before you upload sw.js, change the number in
the line   const CACHE = 'drum-trainer-v4';   to v2, v3 ... Then close and open the app again.

This app uses its own cache name (drum-trainer-...), so it does not touch the piano app.
