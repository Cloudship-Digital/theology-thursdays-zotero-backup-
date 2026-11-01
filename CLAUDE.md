# Rules for Claude in this repository

This repository is the **weekly Zotero backup** for the Theology Thursdays PhD project.

- **NEVER delete, rename, move, overwrite or rewrite anything under `backups/`.** Never force-push, rebase or reset this repository's history.
- The only thing that writes backups is the GitHub Action `.github/workflows/zotero-backup.yml`. It only ever **adds** a new dated folder.
- Claude may read the backups (e.g. to restore or check something) and may fix the workflow if it breaks, but only with the owner's explicit request, and never in a way that touches existing backups.
