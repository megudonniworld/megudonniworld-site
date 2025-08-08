
# Megu Donni World — Static Site Starter

This is a no-code friendly starter. You can deploy it in minutes.

## Files
- `index.html` — main page
- `styles.css` — brand styling
- `images/` — put your artwork here; replace the placeholders
  - `logo.svg` — site logo
  - `hero_placeholder.jpg`, `gallery_*.jpg` — sample placeholders

## How to update images
1. Export your artwork as JPG or PNG.
2. Put the files into the `images/` folder.
3. Open `index.html` and change the `src="images/..."` paths to your filenames.

## Where to host (3 simple options)
### Option A — Netlify (drag & drop)
1. Go to netlify.com, create a free account.
2. Drag & drop the **entire `megu_donni_site` folder** into the dashboard.
3. Done. You get a public URL.

### Option B — GitHub Pages
1. Create a new repository, upload the folder contents.
2. In repo settings → Pages → select branch `main` and `/root` folder.
3. Your site goes live at `https://yourname.github.io/reponame`.

### Option C — Any shared hosting
1. Upload the folder via File Manager or FTP into `public_html`.
2. Make sure `index.html` is at the root of the site.

## Email signup (optional)
- Replace the placeholder form in `#subscribe` with your Mailchimp/ConvertKit embed code.
- Those services give you the HTML snippet—paste it inside the `<section id="subscribe">` area.

## YouTube/Vimeo embedding
- Replace the `src` in the `<iframe>` inside the `#episodes` section with your video link.

## Custom domain
- On Netlify: add your domain in Site Settings → Domain Management.
- On GitHub Pages: add `CNAME` with your domain and set DNS to GitHub Pages IPs.

Enjoy!
