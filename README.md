# Student Showcase Platform

A collaborative frontend project for Mada Studio. Students will design and build a polished platform for presenting student work, using only HTML, CSS, and JavaScript.

## Project overview

This repository is the shared workspace for a real-world-style frontend team. The starter code provides a responsive foundation and page sections for a Navbar, Hero, Projects, About, and Footer. Build each feature through a Jira task, a dedicated branch, and a reviewed Pull Request.

## Run the project

No installation or build step is required.

1. Clone the repository.
2. Open `index.html` in a browser, or use a local development server such as VS Code Live Server.
3. Make changes on your own branch; do not work directly on `main`.

## Team workflow

1. Pick or create a Jira task and assign it to yourself.
2. Create a branch from the latest `main`.
3. Build and test the task locally.
4. Commit focused changes with clear messages.
5. Open a Pull Request, link the Jira task, and request a review.
6. Address feedback, then merge only after approval.

See [the Git workflow](docs/GIT_WORKFLOW.md), [Jira workflow](docs/JIRA_WORKFLOW.md), and [code review guide](docs/CODE_REVIEW_GUIDE.md) for the full process.

## Folder structure

```text
.
├── index.html          # Main entry page
├── pages/              # Additional HTML pages
├── css/                # Stylesheets
├── js/                 # JavaScript files
├── assets/             # Images, icons, and other media
├── docs/               # Team documentation
└── .github/            # GitHub issue and PR templates
```

## Branch naming convention

- `feature/task-name` — new functionality
- `fix/bug-name` — bug fixes
- `style/section-name` — visual or layout changes
- `docs/file-name` — documentation-only updates

Examples: `feature/project-cards`, `fix/mobile-nav`, `style/hero-section`, `docs/git-workflow`.

## Commit messages

Use a short imperative subject, optionally following Conventional Commit style:

- `feat: add project card component`
- `fix: prevent mobile navigation overflow`
- `style: refine hero spacing`
- `docs: clarify PR approval rules`

## Pull Request rules

- One clear task per Pull Request.
- Link the related Jira task.
- Complete the Pull Request template, including screenshots for visual changes.
- Test the change in a browser before requesting review.
- Request at least one reviewer and resolve all conversations before merging.
- Do not merge your own Pull Request unless the team lead has explicitly agreed.

## Jira workflow

Create or select a Jira task, move it to **In Progress** when work begins, and add its link to the branch and Pull Request. Move it to **In Review** when the PR is opened and **Done** only after the PR is merged. Details are in [docs/JIRA_WORKFLOW.md](docs/JIRA_WORKFLOW.md).
