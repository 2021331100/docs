# Documentation Site

A documentation website built with [Mintlify](https://mintlify.com/). It contains getting-started guides, writing and customization help, AI-tool guides, and example API reference pages. Navigation and site appearance are configured in `docs.json`.

## Contents
- Getting started and development guides
- Markdown, code blocks, images, navigation, settings, and reusable snippets
- Guides for Cursor, Claude Code, and Windsurf
- API reference introduction and example endpoint pages

## Tech Stack
- Mintlify documentation platform and CLI
- Markdown / MDX
- JSON configuration

## Project Structure
```text
docs/
├── docs.json
├── index.mdx
├── quickstart.mdx
├── development.mdx
├── essentials/
├── ai-tools/
├── api-reference/
├── snippets/
├── images/
└── logo/
```

## Requirements
- Node.js and npm
- Mintlify CLI

## Run Locally
Install the Mintlify CLI and start the local preview from the directory containing `docs.json`:

```bash
npm install -g mint
mint dev
```

Then open `http://localhost:3000` in your browser. The preview refreshes as you edit documentation files.

## Make Changes
- Edit `docs.json` to change the site name, theme, colors, navigation, logos, and links.
- Add or edit `.mdx` pages in the relevant folder.
- Update the navigation in `docs.json` when adding new pages.
- Keep image and logo paths aligned with the files in the repository.

## Deployment
Connect the repository to a Mintlify deployment through the Mintlify dashboard. Once configured, pushing changes to the connected default branch can publish the updated documentation.

## Useful Links
- [Mintlify documentation](https://mintlify.com/docs)
- [Mintlify quickstart](https://starter.mintlify.com/quickstart)
- [GitHub documentation](https://docs.github.com/)

## Note
This repository currently uses the Mintlify starter-kit structure and sample content. Update the starter site name, links, and example API pages to match your own project before treating them as production documentation.
