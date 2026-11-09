# Putting the Tidepool pages online (GitHub Pages, free)

These three files are the website Apple needs for the Privacy Policy URL and Support URL:
`index.html`, `support.html`, `privacy.html`.

## 1. Contact email (done: poxysstudios@gmail.com)

Open `support.html` and `privacy.html` and replace every `{{EMAIL}}` (two in each file) with the address players and Apple should use. A separate address just for your games is a good idea, since it will be public.

## 2. Create the site

1. Sign in at github.com (or create a free account).
2. Click **+** at the top right, then **New repository**.
   - Name: `tidepool`
   - Public
   - Leave everything else as it is. Click **Create repository**.
3. On the new repo page, click **uploading an existing file**, drag in the three .html files (not this README), and click **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and **/ (root)**, then **Save**.
5. Wait a minute or two, then refresh. The page shows your site address:
   `https://<your-username>.github.io/tidepool/`

## 3. Paste into App Store Connect

- Support URL: `https://<your-username>.github.io/tidepool/support.html`
- Privacy Policy URL (on the App Privacy page): `https://<your-username>.github.io/tidepool/privacy.html`
- Marketing URL (optional): `https://<your-username>.github.io/tidepool/`

Open each link on your phone first to check it loads.
