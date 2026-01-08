# Portfolio Repository Setup Guide

This repository is designed to be shared with potential employers as a professional portfolio showcase.

## Initial Setup

1. **Initialize Git Repository**:
   ```bash
   cd portfolio-repo
   git init
   git add .
   git commit -m "Initial commit: Portfolio repository"
   ```

2. **Create GitHub Repository**:
   - Go to GitHub and create a new public repository
   - Name it something like `portfolio` or `garham-kwon-portfolio`
   - Don't initialize with README (we already have one)

3. **Connect and Push**:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

## Structure

```
portfolio-repo/
├── README.md              # English main page
├── README-KO.md          # Korean main page
├── projects/
│   ├── brainclone.md     # English project detail
│   └── brainclone-KO.md  # Korean project detail
└── resume/               # Resume/CV files (optional)
```

## Adding More Projects

1. Create a new markdown file in `projects/` folder
2. Add a link to it in both `README.md` and `README-KO.md`
3. Follow the same structure as `brainclone.md`

## Customization

- Update contact information in README files
- Add your LinkedIn and GitHub profile links
- Add more projects as you complete them
- Keep the repository updated with your latest work

## Usage

Share the GitHub repository URL with:
- Job applications
- Recruiters
- Networking events
- Professional profiles

The repository serves as a curated showcase of your best work, more professional than sharing a raw GitHub profile.

