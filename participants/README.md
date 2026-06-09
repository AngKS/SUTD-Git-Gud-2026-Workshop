# participants/

This is where your bounty poster lives. 🏴‍☠️

**Do not edit anyone else's folder.** Just create your own:

```
participants/
├── example/          ← a finished example (look, don't touch)
└── <your-username>/  ← YOUR folder goes here
    ├── index.html
    ├── style.css
    ├── paper.jpg
    ├── profile.png
    └── sutd-logo.png
```

## How to make yours

1. Copy the `template/` folder (at the repo root) into here and rename it to your GitHub username:
   - macOS / Linux: `cp -r template participants/<your-username>`
   - Windows (PowerShell): `Copy-Item -Recurse template participants\<your-username>`
   - or just duplicate the folder in your file explorer and rename it.
2. Open `participants/<your-username>/index.html` and edit it to your liking.
3. Replace `profile.png` with your own photo (keep the name `profile.png`, or update the `src` in `index.html`).
4. Commit, push your `branch/<your-username>` branch, and open a Pull Request to `main`.

Once your PR is merged, a robot rebuilds the gallery and your poster shows up at the live page within a minute or two. ✨
