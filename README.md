# Resume Template with GitHub Action

This repository provides a customizable LaTeX resume template with a pre-configured GitHub Action that automatically compiles your resume into a PDF whenever you push changes.

<img width="428" alt="image" src="https://github.com/user-attachments/assets/429f0c3e-949f-4837-bdb5-c6a818396401" />

## Overview

- **Pre-configured GitHub Action**: Automatically builds and generates your resume PDF. You can change to your prefered file name and file path.
- **Customizable Source Files**: Modify content in the `src` folder and update `resume.tex` to suit your needs.
- **Easy Setup**: Once configured, just update your content, push the changes, and the action will run for you.

## Getting Started

### 1. Clone or Fork the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/your-repo.git
```

### 2. Customize Your Resume
- **Update Content: Edit the files inside the `src` folder to update your resume components.
- **Modify `resume.tex`: Adjust or add sections in resume.tex to reflect your personal or professional details.

### 3. Commit and Push Your Changes
After making your changes, commit and push them to trigger the GitHub Action:

```bash
git add .
git commit -m "Customize resume content"
git push origin main
```

### 4. GitHub Action in Action

Once you push your changes:

- **The GitHub Action (located in .github/workflows/) will automatically compile your resume.tex file.
- **The action logs and build results can be viewed under the Actions tab in your GitHub repository.
- **After a successful run, a downloadable PDF of your resume will be available as an artifact.

## Inspiration & Credits

This project draws inspiration from:

- **Audric Serador** – Explore his [SWE Resume Template on Overleaf](https://www.overleaf.com/latex/templates/swe-resume-template/bznbzdprjfyy)
- **SB2NOV** – Check out the [GitHub Resume Repository](https://github.com/sb2nov/resume)

