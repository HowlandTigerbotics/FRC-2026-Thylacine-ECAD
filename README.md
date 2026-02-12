# FRC-2026-Thylacine-ECAD
KiCAD files for Thylacine

To open in KiCAD with Git integration:
1. Go to `File > Clone Project From Repository...`
2. Click the green `<>Code` button on this page, and copy the HTTPS URL
3. Paste the URL as the repository location, then click OK

This will enable change tracking against the current version in the selected branch, as well as committing those changes.

*KiCAD requires a description and username for a commit to actually be pushed within KiCAD.*
*However, the KiCAD push doesn't seem to be working correctly with GitHub credentials.*
*You can still use Git GUI to stage and push commits properly.*
*If a KiCAD push goes wrong and you can't see the commit in Git GUI anymore, check the* `Amend Last Commit`*box and it should reappear in Staged Changed to push again.*

To push changes back to remote (this repository):

1. Make sure that Git for Windows (or equivalent flavor of Git) is installed.
2. Navigate to the local project folder in File Explorer, and open `Git GUI` here (shift right-click to show option).
3. Click `Rescan` if the changed files don't show up under `Unstaged Changes`.
4. Select files under `Unstaged Changes`, go to `Commit > Stage to Commit`, and click `Continue` if a prompt comes up.
5. Add a commit message, and click `Commit` to stage the file changes.
6. Click `Push` and then `Push` again to prompt the Github login popup.
7. Choose the option to login in a new browser window to setup local Git credentials.
8. Finish push, your credentials should be saved for the next push.
