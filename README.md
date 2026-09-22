# iPad 1st Generation — App Archive

A GitHub Pages + GitHub Codespaces-ready web app for browsing an archive of classic iOS applications intended for **iPad 1st Generation** devices.

## Features

* 📱 iPad 1st Generation app archive
* 🔎 Search apps by name, Bundle ID, or version
* 🗂️ Filter by minimum iOS version
* 📦 IPA filename and package information
* 💾 File-size information
* 📁 App Bundle Path
* 🏷️ Bundle ID
* 📲 Install App interface
* ➕ Add to Home Screen support as a Progressive Web App
* 🌐 GitHub Pages compatible
* 💻 GitHub Codespaces compatible
* 📱 Responsive mobile/tablet layout

## App Information

The archive currently contains:

1. Animal Sounds — 2.0
2. SoundTouch — 1.4
3. Tozzle — 3.7
4. AutismXpress — 1.0
5. Lunchbox — 1.4
6. Peek-a-Zoo — 1.1.1
7. Michigan Nature Sounds — 1.0
8. Peek-a-Zoo — 1.0
9. Artsee — 1.1
10. Angry Birds — 1.5.3
11. Farm Flip Fun — 1.0
12. Farm Story — 1.2
13. Stickers — 1.0
14. Forest — 1.1.0
15. Virtuoso — 3.1.2
16. ABC Tracer — 1.8
17. Peek Wild — 2.0.1
18. Peekaboo — 2.0
19. Finding Sight — 2.1
20. ArtikPix — 1.2.4

## Project Structure

```text
ipad-app-archive/
├── index.html
└── README.md
```

## GitHub Codespaces

Open the repository in GitHub Codespaces and serve the project with any static HTTP server.

For example:

```bash
python3 -m http.server 8000
```

Then open the forwarded port in your browser.

## GitHub Pages

1. Push `index.html` and `README.md` to a GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Select the repository branch and `/root` folder.
5. Save.
6. GitHub Pages will publish the archive.

## IPA Files

The page is designed so that actual IPA files can be added later.

Example:

```text
ipa/
├── Animal Sounds 2.0.ipa
├── SoundTouch 1.4.ipa
├── Tozzle 3.7.ipa
└── ...
```

The `index.html` file currently uses placeholder install links. Replace each placeholder with the appropriate IPA URL when the files are available.

## Important

An IPA download link does not by itself guarantee installation on an iPad. Installation depends on the iOS version, application signing/provisioning, device compatibility, and the installation method being used.

The archive is an informational catalog and does not itself provide Apple's signing or distribution services.
