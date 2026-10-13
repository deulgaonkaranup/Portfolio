# Anup Deulgaonkar Portfolio

A static personal portfolio and technical blog built with HTML, Tailwind CSS, and vanilla JavaScript. The site presents a blog-first experience with article listing, category filters, latest article highlights, and a personal About Me section.

## Features

- Blog landing page as the default entry point
- List-style article view with category filtering
- Latest articles sidebar
- Search across article titles and summaries
- Standalone article pages under the articles folder
- About Me section with photo and personal narrative
- Lightweight static setup with no build step required

## Project Structure

```text
Portfolio/
├── index.html            # Main portfolio and blog layout
├── README.md             # Project documentation
├── articles/
│   ├── articles.js       # Article metadata catalog
│   ├── Geospatial-Indexing.html
│   ├── Performance-Tuning.html
│   └── ...
└── assets/               # Optional static assets if added later
```

## Local Development

Because this is a static site, you can run it by opening the HTML directly in a browser or by serving the folder locally.

### Option 1: Open directly

- Open `index.html` in your browser.

### Option 2: Local server

```bash
cd Portfolio
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Notes

- The site uses Tailwind via CDN for styling.
- Blog articles are organized as separate HTML pages for easier expansion.
- The article catalog is stored in `articles/articles.js` and used by the main listing page.

## Customization

To update content:

- Edit the main content in `index.html`
- Add or update article metadata in `articles/articles.js`
- Add new article pages in `articles/`
- Update the personal bio and profile details in the About Me section

## License

This project is for personal portfolio use.
