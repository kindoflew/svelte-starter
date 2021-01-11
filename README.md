# svelte-starter

A basic Svelte boilerplate with:
* [rollup](https://github.com/rollup/rollup)
* [svelte-preprocess](https://github.com/sveltejs/svelte-preprocess)
* [postcss](https://github.com/postcss/postcss)
* [autoprefixer](https://github.com/postcss/autoprefixer)
* [normalize.css](https://github.com/necolas/normalize.css)

Based on the official [Svelte template](https://github.com/sveltejs/template).
This will probably become obsolete after SvelteKit comes out, but I'll periodically 
update dependency versions until it is.

## Getting started

```
npx degit kindoflew/svelte-starter <project-name>
cd <project-name>
npm install
npm run dev
```

Runs on localhost:5000

If you're making an SPA change "start" in package.json to:
```
"start": "sirv public --single"
``` 

