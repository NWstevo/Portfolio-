# Stephen Wiendoh Portfolio

A personal portfolio landing page that can be published directly with GitHub Pages. The page introduces Stephen, lists project categories, and includes a contact call to action.

## Features

- Responsive portfolio landing page
- Hero, about, projects, contact, and footer sections
- Project cards grouped by completed, in-progress, and current work
- Scroll reveal animation for project and about content
- GitHub Pages-ready `index.html`
- Optional Express server for local preview

## Tech Stack

- Node.js
- Express
- HTML
- CSS
- JavaScript

## Project Structure

```text
.
├── package.json
├── package-lock.json
├── README.md
├── index.html
└── server.js
```

## Getting Started

You can open `index.html` directly in your browser, or run the optional local server.

Install the dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

Open the site in your browser:

```text
http://localhost:3000
```

The app uses port `3000` by default. You can also set a custom port with the `PORT` environment variable.

## Publish With GitHub Pages

1. Push this project to a GitHub repository.
2. Open the repository on GitHub.
3. Go to `Settings`.
4. Open `Pages`.
5. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
6. Choose your main branch, usually `main`.
7. Choose the root folder `/`.
8. Click `Save`.

GitHub will publish the site from `index.html`. After it finishes deploying, your portfolio will be available at the URL shown in the Pages settings.

## Customization

- Update the page content in `index.html`.
- Replace `your-email@example.com` with your real email address.
- Edit the project cards to match your latest work.
- Adjust the colors, spacing, and animations inside the `<style>` block.

## Scripts

```bash
npm start
```

Runs the optional Express preview server with `node server.js`.

## License

This project is for personal portfolio use.
