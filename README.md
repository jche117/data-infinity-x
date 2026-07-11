# Data Infinity X — company website

Static website for **Data Infinity X Pty Ltd**, a private AI consulting company focused on Brisbane and the Gold Coast.

## Stack

- Plain HTML, CSS, and JavaScript (no build step)
- Suitable for **GitHub Pages**

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8080

# Node (if you have npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Deploy with GitHub Pages

1. Create a new GitHub repository (public for free Pages, or private with a paid plan).
2. Push this folder as the repo root (or use a `/docs` folder if you prefer).
3. In the repo: **Settings → Pages → Build and deployment**.
4. Set **Source** to **Deploy from a branch**.
5. Choose branch `main` (or `master`) and folder `/ (root)`.
6. Save. After a minute or two, the site will be at:

   `https://<your-username>.github.io/<repo-name>/`

Optional: add a custom domain under **Pages → Custom domain**.

## Customise before launch

| Item | Where |
|------|--------|
| Contact email | `index.html` — `mailto:` link in the Contact section |
| Company legal details | Footer and contact section |
| Brand colours | `styles.css` — CSS variables under `:root` |

## Licence

Site content © Data Infinity X Pty Ltd. All rights reserved.
