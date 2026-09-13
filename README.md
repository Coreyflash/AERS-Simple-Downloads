# AERS Simple downloads

Run your tournament with brackets, table view, puller management, injuries, byes,
and Undo last match.

## Install Simple 1.15.1

Open the [latest release](https://github.com/Coreyflash/AERS-Simple-Downloads/releases/latest)
and choose an installer under Assets:

- Windows: AERS-Simple-1.15.1-Setup.exe. Run setup, then use the desktop shortcut.
- Mac preview: AERS-Simple-1.15.1-Mac-One-App.zip. Move AERS Simple.app to Applications.
  The Mac bundle is unsigned, unnotarized and still needs native Mac acceptance.

Install this version once to connect Simple versions earlier than 1.12 whose updater was disabled.
After that, the app prepares signed updates in the background. Save and close
your event, then reopen to install a ready update. Failed
updates restore the old program and keep saved events, keys and pending exports.

## Select class weights

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
