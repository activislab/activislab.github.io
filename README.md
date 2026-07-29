# ACTIVIS Lab — editorial homepage prototype

This is a no-build static prototype for the new ACTIVIS Lab website. It can be opened locally or published directly with GitHub Pages.

## Preview locally

Open `index.html` in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create or open the repository `activislab/activislab.github.io`.
2. Upload the files in this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and the root `/` folder.
6. Save. The prototype should appear at `https://activislab.github.io`.

## Files

- `index.html`: page structure and draft content
- `styles.css`: complete editorial visual system and responsive layout
- `script.js`: mobile menu, scroll effects and reveal animations
- `.nojekyll`: prevents GitHub Pages from applying Jekyll processing

## Content still to replace

- Team placeholders and portraits
- Correct contact email
- Current publications and links
- Current news items
- Institutional/funding logos and links
- Final joining information
- Optional Portuguese version

## Suggested next stage

After the visual direction and page structure are approved, move the content into reusable data files or an Astro project. This will make people, publications and news easier to update without editing the homepage markup.
