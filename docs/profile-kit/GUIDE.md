# GitHub Profile README Kit 🚀

This kit provides everything you need to build a professional, portfolio-grade GitHub Profile README, just like `ted911`.

## 📁 Directory Structure

- **`templates/`**:
  - `README_TEMPLATE.md`: The main layout file featuring the Bento Grid and Tech Stack sections.
  - `snake.yml`: GitHub Actions workflow to generate the contribution snake animation.
- **`AI_PROMPT.md`**: A ready-to-use prompt to help AI summarize your technical contributions effectively.

## 🛠 Step-by-Step Guide

### 1. Create Your Profile Repository

1. Create a new public repository named **exactly the same as your GitHub username** (e.g., `username/username`).
2. Initialize it with a `README.md`.

### 2. Apply the Layout (Bento Grid)

1. Copy the content of `templates/README_TEMPLATE.md`.
2. Paste it into your profile's `README.md`.
3. **Customize**:
    - Update the **Typing SVG** URL params to match your titles.
    - Update the **Skill Icons** (`skillicons.dev`) in the Bento Grid cells to match your stack.
    - Replace `YOUR_USERNAME` in the GitHub Stats image URL.

### 3. Generate Your Tech Stack Summary

1. Open `AI_PROMPT.md`.
2. Copy the prompt text.
3. Paste it into ChatGPT/Claude along with your project descriptions or resume.
4. Copy the generated Markdown output and paste it into the "Tech Stack & Contributions" section of your README.

### 4. Setup Snake Animation 🐍

1. Create a file in your repository: `.github/workflows/snake.yml`.
2. Copy the content from `templates/snake.yml`.
3. **Commit** the file.
4. Wait for the action to run (runs daily at midnight) or **manually trigger** it via the "Actions" tab.
    - *Note*: If proper permissions are set, it will automatically push the SVG to an `output` branch.
5. In your README, ensure the image source points to:
    `https://raw.githubusercontent.com/<YOUR_USERNAME>/<YOUR_USERNAME>/output/github-contribution-grid-snake.svg`

## ✅ Final Verification

- Check if all images load correctly.
- Verify links to your repositories work.
- Enjoy your new professional profile!
