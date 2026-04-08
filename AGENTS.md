# AI Agent Instructions

This repository is maintained with the help of AI coding agents. If you are an AI agent or assistant working on this project, please adhere to the following guidelines to ensure consistency and maintain the project's standards.

## 1. Project Architecture & Tech Stack

- **Core Technologies**: This project is built using strictly vanilla web technologies: **HTML5**, **CSS3**, and **JavaScript**.
- **No Frameworks**: Do not introduce frameworks or libraries (like React, Vue, Tailwind CSS, or Bootstrap) unless explicitly instructed by the user.
- **No Build Tools**: There are no bundlers (Webpack, Vite), package managers (npm, yarn), or build steps. The code should run directly in the browser.
- **Backend / Server**: This is a static website. There is no backend logic.

## 2. Directory Structure

- `index.html`: The main entry point for the website.
- `assets/css/`: Contains the stylesheets (e.g., `styles.css`). All styling should be done using standard CSS.
- `assets/images/`: Contains all images, icons, and logos.
- `.github/`: Contains GitHub templates and workflows (e.g., Pull Request templates).

## 3. Development Workflow

- **Local Testing**: To test the site locally, either open `index.html` directly in the browser or run a simple local HTTP server:
  ```bash
  python -m http.server
  ```
  Then navigate to `http://localhost:8000`.
- **Styling**: Ensure all new CSS matches the existing design system. Prefer semantic HTML.

## 4. Pull Requests and Contributing

- If contributing new features or bug fixes, always branch off the main branch (e.g., `feature/your-feature-name`).
- Provide clear, descriptive commit messages.
- Always use the provided Pull Request template (`.github/pull_request_template.md`) when opening a PR. Ensure that the checklist is completed and relevant context is linked.

## 5. Edits and Automation

- When modifying files, prefer specific native tools (like code editors/replacers) over generic terminal file editing commands.
- Keep changes concise and localized to the request. Try not to change unrelated parts of the codebase.
