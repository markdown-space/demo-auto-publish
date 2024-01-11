# Demo Auto Publish

This project is used to demonstrate publishing to markdownspace via CLI.

## Project Structure

- `.github/workflows/deploy.yml`: Contains the GitHub Actions workflow for deploying to main branch.
- `markdownspace.config.js`: Configuration file for markdownspace.
- `package.json`: Contains the project metadata and dependencies.
- `pages/`: Contains the markdown and MDX files for the project.

## Setup

1. Clone the repository.
2. Run `npm install` to install the dependencies.
3. Use `npm run publish` to publish the markdown files to markdownspace.

## Pages

- `added_second_doc.md`: A second document in the project.
- `desktopvision.mdx`: An MDX document demonstrating a spinning cube using Three.js.

## Deployment

The project is automatically deployed to the main branch using the workflow defined in `.github/workflows/deploy.yml`.

## Contributing

Please read through our contributing guidelines. Included are directions for opening issues, coding standards, and notes on development.

## License

This project is licensed under the ISC license.