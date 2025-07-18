# Kushwanth Kumar - Portfolio Website

## Deploying to GitHub Pages

1. **Push your code to a GitHub repository.**
   - Create a new repository on GitHub (e.g., `yourusername.github.io` for a user site, or any name for a project site).
   - Push all files, including `.nojekyll`, to the repository.

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub.
   - Click on `Settings` > `Pages` (or `Pages` in the sidebar).
   - Under `Source`, select the `main` branch (and `/root` if prompted).
   - Save.

3. **Access your site:**
   - After a few minutes, your site will be live at `https://yourusername.github.io/` (for user/organization sites) or `https://yourusername.github.io/repository-name/` (for project sites).

4. **Notes:**
   - The `.nojekyll` file ensures GitHub Pages does not process your site with Jekyll, which is important for custom folders and files.
   - Make sure all asset paths in your HTML, CSS, and JS are relative (e.g., `styles.css`, not `/styles.css`).

---

For any issues, refer to the [GitHub Pages documentation](https://docs.github.com/en/pages). 