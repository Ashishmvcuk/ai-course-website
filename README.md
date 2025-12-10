# FRC Learnings – AI Course Website

This repository contains a static website for **FRC Learnings** – Live AI, GenAI, Agentic AI, and GCP DevOps training.

## Structure

```
ai-course-website/
├─ index.html        # Home / Landing page
├─ about.html        # About FRC Learnings
├─ courses.html      # Course catalog
├─ contact.html      # Contact & registration form
├─ assets/
│  ├─ css/
│  │  └─ styles.css  # Custom styling
│  ├─ js/
│  │  └─ main.js     # Minimal shared scripts
│  └─ img/           # Optional images placeholder (currently unused)
└─ README.md         # This file
```

## Local Preview

To preview the site locally, you can open `index.html` in your browser or serve the folder with a simple HTTP server. For example, using Python:

```bash
python -m http.server 8000
```

Then navigate to `http://localhost:8000/` in your web browser.

## Deployment

This site is designed to be deployed using GitHub Pages. Once pushed to your repository, enable GitHub Pages in the repository settings (choose the branch and the root folder), and the site will be live at a URL like `https://<username>.github.io/<repository-name>`.