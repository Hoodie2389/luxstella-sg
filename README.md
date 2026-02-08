# Luxstella.sg Frontpage

This is the static frontpage for Luxstella.sg, designed with a premium, McKinsey-inspired aesthetic.

## Project Structure

- `index.html`: Main HTML file with semantic structure.
- `style.css`: Custom CSS for styling and animations.
- `script.js`: JavaScript for mobile navigation and scroll effects.
- `hero-image.png`: Generated premium hero image.

## How to Deploy to GitHub Pages

1.  **Initialize Git**:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```

2.  **Create a Repository on GitHub**:
    - Go to GitHub and create a new repository (e.g., `luxstella-site`).
    - Do *not* initialize with a README, .gitignore, or license (since you have local files).

3.  **Push to GitHub**:
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/luxstella-site.git
    git branch -M main
    git push -u origin main
    ```

4.  **Activate GitHub Pages**:
    - Go to your repository **Settings**.
    - Click on **Pages** in the left sidebar.
    - Under **Build and deployment**, select **Source** as `Deploy from a branch`.
    - Select `main` branch and `/ (root)` folder.
    - Click **Save**.

Your site will be live at `https://YOUR_USERNAME.github.io/luxstella-site/` shortly!
