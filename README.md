# Silver Racing NFC 3D Viewer

This folder is a GitHub Pages-ready website for the Silver Racing STEM Racing NFC tag.

## Upload to GitHub

1. Create a new GitHub repository (for example `silver-racing-3d`).
2. Upload `index.html` and the `models` folder exactly as they are.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. GitHub will give you a public URL such as:
   `https://YOUR-USERNAME.github.io/silver-racing-3d/`

## NFC

Write that public URL to the NFC tag as a URL/URI record.

The STL is loaded by the webpage from:
`models/front-wheel-support.stl`

The viewer uses Three.js from jsDelivr, so the judge's phone needs internet access.
