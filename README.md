# Yifan Chen Scholar Homepage

This is a free, static academic homepage designed for GitHub Pages.

## Edit the content

- Open `index.html`.
- Replace the placeholder bio, research directions, email, affiliation, and links.
- The homepage portrait is fixed in the hero image `src` in `index.html`.
- The Photography section randomly selects ten images from the `photoPool` list
  at the bottom of `index.html`.
- Add new photos to `assets/`, then add their paths to `photoPool` if you want
  them to appear in Photography.
- Image filenames currently avoid Chinese prefixes for simpler GitHub Pages
  paths.
- Add your CV as `cv.pdf` in this folder, or update the CV link in `index.html`.

## Publish on GitHub Pages

1. Create a GitHub repository named `yourusername.github.io`.
2. Upload all files from this folder to that repository root.
3. Go to repository `Settings` -> `Pages`.
4. Set the source to the main branch root.
5. Your site will be available at `https://yourusername.github.io`.

## Notes

GitHub Pages cannot automatically read the contents of an `assets/` folder, so
new image files must be added to the `photoPool` list before they can appear on
the site.
