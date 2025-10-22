# JavaScript Projects

A repository to store JavaScript projects, experiments, and small web utilities.

## Table of Contents
- About
- Typical contents
- Requirements
- Run locally
- Recommended structure
- Testing & linting
- How to contribute
- Roadmap
- License & Contact

## About
This repo contains front-end JavaScript experiments and Node.js utilities. Projects may be browser-based (vanilla JS) or Node-based (CLI/tools).

## Typical contents
- Browser examples: vanilla JS projects, DOM manipulation demos
- Node utilities: small scripts, parsers, automation
- Demos using modern JS features (ES6+)

## Requirements
- For browser projects: modern browser
- For Node projects: Node.js 14+ (or as specified per project)
- Optional: npm or yarn

## Run locally
Browser projects:
- Open `index.html`, or run a local server (Live Server, python -m http.server)

Node projects:
- Install dependencies: npm install
- Run: node src/index.js or npm run start (if package.json configured)

## Recommended structure
- /project-name/
  - package.json (for Node projects)
  - index.html (for browser)
  - src/
  - assets/
  - README.md (project-specific)

## Testing & linting
- Use Jest or Mocha for unit tests (Node)
- Use ESLint for code style: npm install eslint --save-dev
- Add a `test` script in package.json for convenience

## How to contribute
- Add a new folder for your project with a short README
- Follow consistent naming and include run instructions
- Keep DOM-manipulation minimal and clean up event listeners
- Open a PR with a description and screenshots (if UI-related)

## Roadmap ideas
- Add small UI components library (tabs, modals, accordions)
- Create more Node command-line utilities
- Add interactive demos with step-by-step explanations

## License & Contact
Add a LICENSE file if sharing is permitted. Contact: https://github.com/stectorius
