# MJ B Ferialde - Personal Portfolio

A warm orange-and-cream personal website built with plain HTML, CSS, and a little JavaScript.
No frameworks, no database, no build step.

## Project structure

```
mj-portfolio/
├── index.html          (all page content)
├── style.css           (all styling and colors)
├── README.md
└── assets/
    ├── profile.jpg     (your profile picture, shown in the hero)
    ├── photos/         (photo-1.jpg to photo-6.jpg, for "My photos")
    └── childhood/      (childhood-1.jpg to childhood-3.jpg)
```

## 1. Replace the placeholder pictures first

The images in this ZIP are orange placeholders. To use your own:

1. Rename your picture to exactly `profile.jpg` and overwrite `assets/profile.jpg`.
   A portrait (taller than wide) photo works best.
2. Do the same for `assets/photos/photo-1.jpg` ... `photo-6.jpg` and
   `assets/childhood/childhood-1.jpg` ... `childhood-3.jpg`.
3. Keep the same file names (and `.jpg`) and nothing else needs changing.
   If your photo has another extension such as `.png`, also update the `src="..."` in `index.html`.
4. Edit the captions in `index.html` (search for `<figcaption>`).

Tip: keep each photo under about 500 KB so the site loads fast.

## 2. Edit your words

Open `index.html` in any text editor (Notepad, VS Code) and change the text in the
Childhood, Hobbies, Favorites, and Dreams sections. Colors are at the top of `style.css`.

## How to extract the ZIP file

- **Windows:** right-click the ZIP, choose **Extract All...**, then **Extract**.
- **Mac:** double-click the ZIP.
- **Phone:** use a Files app that can unzip (e.g. Files by Google, ZArchiver).

## How to open the website locally

Open the extracted folder and double-click `index.html`. It opens in your browser.

## How to upload the files to GitHub

1. Create a free account at https://github.com and sign in.
2. Click **+** (top right), then **New repository**.
3. Name it `mj-portfolio` (or `yourusername.github.io` for a shorter web address).
   Set it to **Public** and click **Create repository**.
4. Click **uploading an existing file**.
5. Open the extracted folder and drag **everything inside it** (`index.html`, `style.css`,
   `README.md`, and the `assets` folder) into the GitHub page.
   Important: upload the files themselves, not the ZIP, and make sure `index.html` is at the top level.
6. Click **Commit changes**.

## How to enable GitHub Pages

1. In your repository, open **Settings**, then **Pages** in the left menu.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**, then click **Save**.
4. Wait 1 to 3 minutes and refresh the page.

## How to access the published website

Your address will be shown at the top of the Pages settings:

- `https://YOUR-USERNAME.github.io/mj-portfolio/`
- or, if you named the repository `YOUR-USERNAME.github.io`: `https://YOUR-USERNAME.github.io/`

To update the site later, upload the changed files again and commit. It refreshes automatically.
