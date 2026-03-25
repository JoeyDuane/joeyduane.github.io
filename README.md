# joeyduane.github.io
My personal blog.

## Project Overviw
This project is a personal blog system built with the Hugo framework and deployed on Github Pages. It's mainly used to record technical notes, academic reasrch progress and daily journals. The goal is to keep it concise, efficient and easy to retrive, while ensuring code maintainbility and content consistency.

## Technical Stack
- Framework: Hugo (Extended Version)
- Deployment: GitHub Actions + GitHub Pages
- Content Format: Markdown (with YAML front matter)
- Styling: SCSS / Tailwind CSS (to be decided per theme)
- Version Control: Git

## Core Principle & Rules
- **Language Consistency**: Blog body content uses Chinese. All code comments, Git Commit Message, logic explanations and technical documention uses English.
- **Code Quality**: Follow Hugo best practice (Baseof/List/Single template structure). Explanation modification logic before changing config or templates.
- **Content Management**: New posts automatically generate compliant Front Matter (Title, Fate, Tags, Categories, Draft). Keep directory structure clear ('/content/post/' for tech & academic articles, '/content/journals/' for personal logs).
- **Long-term Maintenance**: After major changes, update README.md or TODO.md. Regularly check Hugo version compatibility and Github Actions workflow status.