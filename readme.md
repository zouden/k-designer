# K-Designer 🐟

### A tool for designing genotyping primers.

## Usage

### Initial Setup

Requires [Node.js](https://nodejs.org/en/)

```sh
git clone https://github.com/zouden/k-designer.git
cd k-designer
npm install
npm run build
```

### Web interface

1. Launch the web server by running `npm start`
1. Open a browser and connect to [localhost:5000](http://localhost:5000).


## Development

### Get started

After installing dependencies with `npm install`, start the server in watch mode using [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see the app running. Make a change to `src/App.svelte`, save it, and the page should automatically reload showing your changes.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode).

### Building and running in production mode

To create an optimised version of the app:

```bash
npm run build
```

You can run the newly built app with `npm start`. This uses [sirv](https://github.com/lukeed/sirv), which is included in your package.json's `dependencies` so that the app will work when you deploy to platforms like [Heroku](https://heroku.com).

### Deploying to the web

#### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

#### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
surge public my-project.surge.sh
```
