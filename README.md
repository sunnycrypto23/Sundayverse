# Your personal site

A simple, fast, free website — a homepage/portfolio plus a blog ("the log").
No build tools, no database. Just HTML, CSS, and plain files.

## 1. Personalize it

Open these files in any text editor (or right on GitHub, see below) and
replace the placeholder text:

- `index.html` — your name, intro, "about me" cards, contact links
- `blog.html` — list of posts (already matches the two sample posts)
- `posts/starting-this-blog.html` and `posts/second-post.html` — real posts,
  or delete/replace with your own

Every page has `Your Name` and `you@example.com` in a few places — find and
replace those first.

## 2. Add a new blog post

1. Copy `posts/second-post.html`, rename it (e.g. `posts/my-new-post.html`).
2. Edit the title, tags, date, and body text inside.
3. Add a matching `<li><a class="log-entry" href="posts/my-new-post.html">...`
   block to the top of the list in both `index.html` (latest entries) and
   `blog.html` (full list).

## 3. Put it online for free — GitHub Pages

1. Create a free account at https://github.com if you don't have one.
2. Click "New repository". Name it exactly `your-username.github.io`
   (replace `your-username` with your actual GitHub username).
3. Make it Public, then click "Create repository".
4. On the new repo page, click "uploading an existing file" and drag in
   all the files/folders from this project (`index.html`, `blog.html`,
   `css/`, `posts/`, `quiz/`). Commit the changes.
5. Go to the repo's **Settings → Pages**. Under "Source", pick the `main`
   branch and `/ (root)`, then Save.
6. Wait 1–2 minutes. Your site will be live at:
   `https://your-username.github.io`

That's it — free hosting, a real public URL, no expiry. Any time you push a
new file, the live site updates automatically within a minute or two.

### Alternative: Netlify or Vercel
If you'd rather not use GitHub Pages, you can drag-and-drop this whole
folder onto https://app.netlify.com/drop for an instant free URL — no
account setup required for the first deploy.

## 4. Using a custom domain (optional, not free)
GitHub Pages gives you a free `.github.io` address. If you later want
`yourname.com`, you'd buy a domain (~$10–15/year from somewhere like
Namecheap) and point it at GitHub Pages — the free hosting itself stays free.
