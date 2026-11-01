# heology-thursdays-zotero-backup
## Daily Zotero backup
- Every **day at 06:17 UTC** (and on demand via *Actions → Daily Zotero backup → Run workflow*), a GitHub Action downloads the Zotero library (records, collections, notes, highlights and comments) and **adds** a dated folder `backups/YYYY-MM-DD/`. It never edits or deletes old ones.
- Secrets used: `ZOTERO_API_KEY` (read-only), `ZOTERO_USER_ID`, and optionally `ZOTERO_GROUP_ID`.
- PDFs are not included (they stay in Zotero Storage). For a full offline copy, use Zotero desktop: *File → Export Library… (Zotero RDF, Export Files)*.
