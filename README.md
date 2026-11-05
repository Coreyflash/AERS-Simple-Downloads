# AERS Simple downloads

Run your tournament with brackets, table view, puller management, injuries, byes,
and Undo last match.

## Install Simple 2.0.33

Open the [latest release](https://github.com/Coreyflash/AERS-Simple-Downloads/releases/latest)
and choose an installer under Assets:

- Windows: AERS-Simple-2.0.33-Setup.exe. Run setup, then use the desktop shortcut.
- Mac: use AERS-Simple-2.0.33-Mac-Guided-Setup.pkg, or move the app from the Mac ZIP or disk image to Applications.
  Supports Intel and Apple Silicon on macOS 13.5 or newer. The app and installer are unsigned and unnotarized; follow the included install guide.

Install this version once to connect Simple versions earlier than 1.12 whose updater was disabled.
After that, the app prepares signed updates in the background. Save and close
your event, then reopen to install a ready update. Failed
updates restore the old program and keep saved events, keys and pending exports.

## More room to run the event

The compact header groups Setup, Pullers, Run event, Completed and Results on
the left, with Second bracketer and Save now on the right. Event health opens
beside Edit pullers when needed. In Bracket view, use **Table** to jump to the
active class at another table without changing its queue or results.

**Pop out bracket** appears in Bracket view; **Pop out live tables** appears in
Live tables. Expand bracket gives the bracket more room; Escape returns.
Windows launches maximize the new Simple window and reset its browser zoom
without changing Windows display scaling. A window left in the background
does not receive startup keyboard input.

## Import pullers into existing classes

Build the classes in Setup first. In Pullers, choose **Import pullers to classes**
and download the template. Enter each person's full first and last name on one
row and put **X** under every class they enter. Keep the class headings unchanged
and save as CSV.

Choose the completed CSV, review all database name matches and explicitly confirm
new pullers. Review each class rating, then confirm the import. Missing class
ratings are clearly marked as the default 1500. Import cannot create unknown
classes, duplicate registered people, override tiers, or change scored classes.
Import and automatic saves stay local; results require an explicit submission.

Done stays below the welcome banner so Dismiss is accessible. On Windows,
relaunching reuses the matching healthy service even if a previous window's close
notification was lost. X keeps the service available; use **Done → Save & close
for now** for normal shutdown.

## Select class weights

Choose Custom class… to enter a name such as First Timers. Its displayed name stays in the event; the CSV CLASS column exports it as `open`.

Use Add class in Brackets to create and register another class after existing brackets start. Existing class entries, brackets and results remain protected. Re-randomize this class can be used repeatedly before its first match decision. A recorded winner, BYE or injury locks it, including after Undo or reopening the event.

In Setup, tap any of the preset weights, or add a custom weight from 0 to 999
with an optional +. Select Right, Left or Both, choose a table, then add the
classes together. The selection stays ready for the next division.

## Save and send results

Save now confirms an encrypted local event backup. For unfinished work, use
Done → Save & close for now. When the event is complete, review Done → Finish &
send results to submit it. Only that explicit action or Send now queues delivery;
typing, importing pullers, autosave, refresh and closing stay local. Approved
queued results retry while AERS runs and at the next startup. A successful receipt
confirms delivery; offline files remain saved.

Drive receives Event Name.csv. Repeating the same saved export reuses its file;
different saved result snapshots retain separate files with that event name.
Practice/demo results stay local. Published installers include the protected
ratings and results connections and verify them before release.

The source repository is private. These installer/update files are public. The
app contains no release-signing private key or publishing credential. Windows
setup is not Authenticode-signed; signed update manifests authenticate updates
separately.

Version 1.15.1: faster opening with signed updates prepared in the background, plus the navy/red/blue AERS website palette and clearer controls.

Events save automatically. Use Saved events to reopen an event or find its files.
Done lets you save and close unfinished work or explicitly finish and send results.
