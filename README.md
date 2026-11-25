# HashCat Website

A multi-page, static website built with **HTML** and **CSS**. It presents HashCat with a landing page, an about page, installation instructions, documentation, and an archive of older versions.

<!-- Add a screenshot: save it in /images and uncomment the line below -->
<!-- ![HashCat website preview](images/preview.png) -->

## Live Demo

[Add your live link here, e.g. a GitHub Pages URL]

## Pages

| Page | File | Purpose |
| --- | --- | --- |
| Home | `index.html` | Landing page and main entry point |
| About | `about.html` | Background on the project |
| Install | `install.html` | Step-by-step installation guide |
| Documentation | `documentation.html` | Usage and reference documentation |
| Older Versions | `older_version.html` | Archive of previous releases |

## Project Structure

```
HashCat/
├── images/              # Images and visual assets
├── index.html           # Home page
├── about.html           # About page
├── install.html         # Installation guide
├── documentation.html   # Documentation
├── older_version.html   # Previous versions
└── styles.css           # Shared stylesheet
```

## Built With

- **HTML5**: page structure and semantic markup
- **CSS3**: a single shared stylesheet (`styles.css`) for consistent styling across all pages

## Getting Started

No build step or dependencies are needed.

1. **Clone the repository**
   ```bash
   git clone https://github.com/md-omar-faroque/HashCat.git
   cd HashCat
   ```

2. **Open the site**
   - Double-click `index.html`, or
   - Serve it locally:
     ```bash
     # Python 3
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000`.

## Deployment

Because the site is fully static, it can be hosted anywhere. To use **GitHub Pages**:

1. Go to **Settings → Pages** in the repository.
2. Under **Source**, choose the `main` branch and the `/ (root)` folder.
3. Save, and your site will be published at `https://md-omar-faroque.github.io/HashCat/`.

## Customization

- **Styling:** edit `styles.css`. Changes apply to every page.
- **Content:** edit the matching `.html` file for each page.
- **Images:** place new assets in `images/` and reference them with relative paths.

## Contributing

Suggestions and improvements are welcome.

1. Fork the repository
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Author

**Md Omar Faroque**
GitHub: [@md-omar-faroque](https://github.com/md-omar-faroque)

## License

No license has been specified yet. Consider adding one, such as [MIT](https://choosealicense.com/licenses/mit/), if you want others to reuse the project.
