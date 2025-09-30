asdf
[NIS 2025 Webapp]

This is a simple Node.js/Express boilerplate for an Azure webapp.

## Getting Started

1. Install dependencies:
	```bash
	npm install
	```
2. Run locally:
	```bash
	npm start
	```
	The app will be available at http://localhost:3000

## Project Structure
- `server.js` — Express server
- `public/index.html` — Start page
- `package.json` — Project config

## Deploying to Azure
1. Push your code to a GitHub repo (or Azure Repos).
2. Create an Azure Web App in the Azure Portal.
3. Configure deployment source to your repo.
4. Azure will install dependencies and run `npm start` automatically.

For more details, see [Azure Web App documentation](https://learn.microsoft.com/en-us/azure/app-service/).