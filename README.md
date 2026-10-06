# AERS Simple downloads

Run your tournament with brackets, table view, puller management, injuries, byes,
and Undo last match.

## Install Simple 1.15.32

Open the [latest release](https://github.com/Coreyflash/AERS-Simple-Downloads/releases/latest)
and choose an installer under Assets:

- Windows: AERS-Simple-1.15.32-Setup.exe. Run setup, then use the desktop shortcut.
- Mac: use AERS-Simple-1.15.32-Mac-Guided-Setup.pkg, or move the app from the Mac ZIP or disk image to Applications.
  Supports Intel and Apple Silicon on macOS 13.5 or newer. The app and installer are unsigned and unnotarized; follow the included install guide.

Install this version once to connect Simple versions earlier than 1.12 whose updater was disabled.
After that, the app prepares signed updates in the background. Save and close
your event, then reopen to install a ready update. Failed
updates restore the old program and keep saved events, keys and pending exports.

## Select class weights

Choose Custom class… to enter a name such as First Timers. Its displayed name stays in the event; the CSV CLASS column exports it as `open`.

Use Add class in Brackets to create and register another class after existing brackets start. Existing class entries, brackets and results remain protected. Re-randomize this class can be used repeatedly before its first match decision. A recorded winner, BYE or injury locks it, including after Undo or reopening the event.

In Setup, tap any of the preset weights, or add a custom weight from 0 to 999
with an optional +. Select Right, Left or Both, choose a table, then add the
classes together. The selection stays ready for the next division.

## Save and send results

Save event keeps an encrypted .aersflash backup in AERS Simple/Saves in your home
folder. It also protects a pending match-results export. With the organizer's
results connection configured, sending retries automatically while AERS runs and
at next startup. A successful receipt confirms delivery. Offline files stay saved.

Drive receives Event Name.csv. Repeating the same saved export reuses its file;
different saved result snapshots retain separate files with that event name.
Practice/demo results stay local. Windows can reuse an existing Full connection
for the same Windows user; other computers need the organizer's connection once.

The source repository is private. These installer/update files are public. The
app contains no release-signing private key or publishing credential. Windows
setup is not Authenticode-signed; signed update manifests authenticate updates
separately.

Version 1.15.1: faster opening with signed updates prepared in the background, plus the navy/red/blue AERS website palette and clearer controls.

Events now save automatically. Use My events to reopen an event or find its files. Select Done before leaving to save and queue current results.
