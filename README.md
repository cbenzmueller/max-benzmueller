# Max Benzmüller — Sports CV

Static single-page site served via GitHub Pages at
<https://cbenzmueller.github.io/max-benzmueller/>.

- `index.html` — the whole page (no build step, no dependencies)
- `img/` — photos, resized to ≤1600px and stripped of metadata (EXIF/GPS)

To add a photo: `convert in.jpg -strip -resize '1600x1600>' -quality 82 img/name.jpg`
