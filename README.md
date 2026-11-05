# SDAfriends

A simple four-page website (Home, About us, News, Connect) for the SDA Songs Channel on YouTube and the S.D.A Channel and Seventh Day Adventist Friends pages on Facebook.

It is a single static file (`index.html`) with no build step and no dependencies. Pages switch with the URL hash (`#home`, `#about`, `#news`, `#connect`), so it works on GitHub Pages as is.

## Publish as a GitHub Pages demo

1. Create a new repository on GitHub, for example `sdafriends`.
2. Upload `index.html`, `README.md` and `.nojekyll` to the repository root.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then save.
5. After a minute, the site is live at `https://YOUR-USERNAME.github.io/sdafriends/`.

## Edit the content

Open `index.html` and change the text inside each `<section class="page">`. Colors are set at the top of the `<style>` block.
