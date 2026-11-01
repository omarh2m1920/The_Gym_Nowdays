# A little brighter · For Myriam

A tiny surprise: tap the hanging bulb to turn a quiet, dark gym into a warm one.

## Preview it

Unzip the download, open the `myriam-gym` folder, and double-click `index.html`.
No installation or build step is needed. Tap the bulb again to replay the effect.

## Publish on GitHub Pages

1. Create a repository on GitHub. A public repository works with GitHub Free.
2. Open the repository, choose **Add file → Upload files**, and upload the
   **contents** of `myriam-gym`: `index.html`, the `assets` folder, and `.nojekyll`
   (if visible). You can upload this README too. Keep `index.html` at the root of
   the repository, with `assets` next to it. Upload the extracted files, not the ZIP.
3. Commit the files to the `main` branch.
4. Go to **Settings → Pages**. Under **Build and deployment**, choose
   **Deploy from a branch**, select **main** and **/ (root)**, then click **Save**.
5. Once GitHub finishes publishing, your link will appear on that Pages screen.
   A typical address is `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.
6. Open the link on your phone, tap the bulb, and send the link to Myriam.

Official guide: [Configure a GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Change the words or photo

- Open `index.html` in any text editor to change the visible heading or message.
  If you edit the words, also update the heading's `aria-label` and the matching
  text in the script at the bottom for screen readers.
- Replace `assets/gym.jpg` with another image of the same filename to change
  the background. The supplied photo is included as provided.

## Included

- `index.html` — all layout, bulb artwork, animation, and interaction.
- `assets/gym.jpg` — the supplied gym photo.
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files.
- `README.md` — these instructions.

The site uses relative asset paths, so it works on a GitHub Pages project URL
as well as when opened locally. It has no external fonts, packages, analytics,
music, or network dependencies. It supports keyboard controls, touch, and
reduced-motion preferences. Every visit starts with the light off.
