MEDSTUDY - Android project (works offline)

BUILD THE APK ONLINE WITH GITHUB (no installs)
 1. Go to github.com/new (not "Import") and create a Public repository named MedStudy.
 2. Upload everything inside this folder (not the folder itself).
 3. Actions tab > "set up a workflow yourself", delete the text, paste the contents
    of build-workflow-copy.yml, then Commit changes.
 4. Wait 3-5 minutes for a green tick. Open the run and download "MedStudy-APK".
 5. Unzip it to get app-debug.apk, copy it to your phone, tap it, and allow
    "install unknown apps".

IMPORTANT: your notes are stored inside the app. Before you install a NEWER build,
open the Backup tab and copy your notes, because installing a new build may require
uninstalling the old one, which erases its notes. Paste them back under Restore.

To change the app, edit app/src/main/assets/index.html.
