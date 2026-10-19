# novendrastywn.github.io

Personal academic page of Novendra Setyawan, migrated from Google Sites.

## Files

- `index.html` – all content (Bio, Education, Work, Reviewer, Publications, Teaching, Project)
- `style.css` – styles, with automatic dark mode
- `assets/profile.jpg` – profile photo (add it yourself; initials "NS" show until then)
- `.nojekyll` – serve files as-is, no Jekyll build

## Deploy

1. Create a public repo named exactly `novendrastywn.github.io`.
2. Push these files to the `main` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial academic page"
   git branch -M main
   git remote add origin https://github.com/novendrastywn/novendrastywn.github.io.git
   git push -u origin main
   ```
3. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `/ (root)`.
4. Site goes live at `https://novendrastywn.github.io` after a minute or two.

## Editing

- New publication: copy an `<li>` inside the matching `<ol class="pubs">`.
- New course: uncomment the card template in the Teaching section.
