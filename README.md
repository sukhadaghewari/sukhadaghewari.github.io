# My website

This repository is your personal website, published free by GitHub Pages at
`https://yourusername.github.io`.

---

## 1. Publish it (once, about 15 minutes)

1. Sign in to [github.com](https://github.com). Your username becomes your web address.
2. Click **+** (top right) → **New repository**.
   Name it exactly **`yourusername.github.io`**, using your own username.
   Choose **Public**, then click **Create repository**.
3. On the new, empty repository page, click **uploading an existing file**.
   Drag in everything inside this folder, including the folders that start with `_`
   (`_layouts`, `_includes`, `_posts`, `_templates`) and `assets`. Click **Commit changes**.
   If folders won't upload, use Chrome or Edge.
4. Open **Settings → Pages**. Under *Build and deployment*, set **Source** to
   *Deploy from a branch*, **Branch** to `main` and the folder to `/ (root)`. Click **Save**.
5. Open the **Actions** tab. When the latest run shows a green tick (1–2 minutes),
   your site is live at `https://yourusername.github.io`.

## 2. Make it yours (first time)

Text in **[square brackets]** is a placeholder. Replace it before you share the link.

| File | What it controls |
|---|---|
| `_config.yml` | Your name, tagline, location, topics, links, photo, cover photo |
| `index.md` | Home page: About, Selected work, News |
| `assets/cv.pdf` | Your CV. The **Download CV** button under your name links to it (upload yours with this exact name) |
| `assets/img/photo.jpg` | Your photo (square). Then remove the `#` before `photo:` in `_config.yml` |
| `assets/img/cover.jpg` | Your cover photo. See *Cover photo* below |
| `_posts/` | Blog posts. Rewrite or delete the starter post |

The browser-tab icon shows the first letter of your name automatically.

The moon button at the top right switches the site between light and dark. Visitors first see
whichever their device uses, and the site remembers their choice once they press it.

### Cover photo

The cover is the wide strip at the top of the home page, with your photo overlapping it.

1. Crop your photo to a wide strip, about 3 times as wide as it is tall (for example 2400 × 750 pixels).
   Keep what matters in the middle: laptops show a thin band across it, phones a taller slice.
2. Save it as a JPG under about 500 KB. The free site [squoosh.app](https://squoosh.app) can shrink it.
3. Open `assets/img` → **Add file** → **Upload files**, upload it named `cover.jpg`, then **Commit changes**.
4. In `_config.yml`, change `cover: /assets/img/cover.svg` to end in `.jpg`.
   - If the crop cuts off the part you like, set `cover_position` to `top` or `bottom`.
   - To hide the cover, put a `#` at the start of the `cover:` line.

## 3. Everyday updates

Every change works the same way: open the file on github.com, click the **pencil** icon,
edit, then click **Commit changes**. The site updates in about a minute.

| I want to… | Do this |
|---|---|
| Add a news item | `index.md` → add a line at the top of the News list: `- **Oct 2026** What happened.` |
| Add a project | `index.md` → copy one `###` block under *Selected work* and edit it |
| Update my CV | Upload a new `assets/cv.pdf`. The same name replaces the old one |
| Change a link or my tagline | `_config.yml` |
| Change the colours, fonts or text sizes | The first two blocks of `assets/css/site.css`: the light theme (with fonts and sizes), then the dark theme |

## 4. Write a blog post

1. Open the `_posts` folder → **Add file** → **Create new file**.
2. Name it `YYYY-MM-DD-short-title.md`, for example `2026-10-05-first-results.md`.
   The date becomes the post's date. Use lowercase and dashes, no spaces.
3. Paste this at the very top, then write underneath in plain text:

   ```
   ---
   title: "Your post title"
   description: "One sentence shown under the title and on the Blog page."
   tags: [Climate]
   ---
   ```

4. Click **Commit changes**.

### Topics

The `tags` line puts a post under one or more topics, for example `tags: [Climate, Forests]`.
Each topic appears in the Blog's left column; clicking it shows only those posts.
Spell topics the same way every time: `Climate` and `climate` would become two topics.

For headings, links, images, quotes, code, equations and footnotes, copy from the
cheat sheet in **`_templates/new-post.md`**.

### Add an image

1. Open `assets/img/posts` → **Add file** → **Upload files** → drop your image → **Commit changes**.
2. In your post, write:

   ```
   ![What the image shows](/assets/img/posts/your-image.jpg)
   *An optional caption, on the line right below.*
   ```

Keep images under about 1 MB: JPG for photos, PNG for charts. Use lowercase file names with dashes.

**Cover image (optional):** add `image: /assets/img/posts/cover.jpg` to the post's top section.
It appears under the title and when the post is shared on LinkedIn.

### Drafts and equations

- **Hide a post while you work on it:** add `published: false` to its top section. Delete the line to publish.
- **Equations:** add `math: true` to the top section, then write `$$ E = mc^2 $$`.

## 5. If something goes wrong

- Open the **Actions** tab. A red ✗ means the last change didn't build. Click it to read the error.
  Your live site keeps showing the last working version until you fix it.
- Most errors come from a post's top section: keep both `---` lines, put the title in
  "double quotes", and indent with spaces, never tabs.
- To undo a change, open the file → **History**, open an earlier version, and copy its text back.

## Optional extras

- **Edit several files at once:** press `.` on your repository page to open a full editor in the browser.
- **Your own domain** (for example `yourname.com`): buy one, then add it under **Settings → Pages → Custom domain**
  and follow GitHub's DNS steps.
