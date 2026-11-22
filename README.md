# app-updates

New versions of two small personal Android apps, **Tend** and **Arc**, so they can update themselves from inside the app.

- `tend.json` and `arc.json`: the newest version of each (version number, download link, SHA-256 checksum, one line of notes).
- The APK files themselves are attached to this repo's Releases.

Each app checks its file at most once a day, when it's opened, and downloads a new version only when its Update
button is tapped. Android only installs an update signed with the same key as the app already on the phone, and asks
the person to confirm every time.

No code and no personal data live here.
