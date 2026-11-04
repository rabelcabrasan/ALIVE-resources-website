# ALIVE Resources Website

A free website for sharing ALIVE (Arabic Language and Islamic Values Education)
teaching materials: books, PPTs/worksheets, the attendance system, and the
Android app.

## How to publish this for free on GitHub Pages

1. Go to https://github.com and sign in to your account.
2. Click the **+** icon (top right) → **New repository**.
   - Repository name: `alive-resources` (or any name you like)
   - Keep it **Public**
   - Do NOT add a README, .gitignore, or license (this project already has one)
   - Click **Create repository**
3. On the new repo's page, click **uploading an existing file**.
4. Drag in every file and folder from this project (keep the same folder
   structure: `index.html`, `about.html`, `contact.html`, the `css/`, `js/`,
   `downloads/`, and `files/` folders).
5. Click **Commit changes**.
6. Go to the repo's **Settings** tab → **Pages** (left sidebar).
7. Under "Build and deployment", set **Source** to **Deploy from a branch**,
   branch **main**, folder **/ (root)**. Click **Save**.
8. Wait 1-2 minutes, then refresh the Pages settings page. Your live link
   will appear, looking like:
   `https://your-github-username.github.io/alive-resources/`

That link is your permanent, free website. Share it with anyone.

## How to add a book, PPT, the app, or the attendance system

1. Put the actual file inside the matching folder:
   - Books → `files/books/`
   - PPTs/worksheets → `files/lessons/`
   - Attendance system installer → `files/attendance-system/`
   - Android app (.apk) → `files/app/`
2. Open the matching page in `downloads/` (e.g. `downloads/books.html`) in
   a text editor.
3. Copy one of the commented example `<li class="file-item">...</li>` blocks,
   paste it into the `<ul class="file-list">` section, and edit the name and
   the `href` to point to your new file.
4. Save, then upload the changed file (and the new file in `files/`) to your
   GitHub repo the same way as step 4 above — GitHub will ask if you want to
   replace the existing file; say yes.
5. GitHub Pages updates automatically within a minute or two.

## Before you publish

- Open `contact.html` and replace the placeholder email with the one you
  want the public to use.
- Large files (apps, big PDFs): GitHub works well up to ~25 MB per file
  through the web upload. For bigger files, Google Drive + a download link
  works too — just point the button's `href` at that link instead.
