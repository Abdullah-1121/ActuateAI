# Actuate-AI Documentation

This website contains the documentation for Actuate-AI: Physical AI & Humanoid Robotics Textbook, built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## Installation

```bash
npm install
```

## Local Development

```bash
npm run start
```

This command starts a local development server and opens up a browser window at http://localhost:3000. Most changes are reflected live without having to restart the server.

## Build

```bash
npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using npm:

```bash
npm run deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Project Structure

- `/docs`: Contains the documentation content in Markdown format
- `/src`: Contains custom React components and styling
- `/static`: Contains static assets like images and favicons
- `docusaurus.config.js`: Main configuration file
- `sidebars.js`: Navigation sidebar configuration
