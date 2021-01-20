# svelte-starter

A basic Svelte boilerplate with:
* [rollup](https://github.com/rollup/rollup)
* [tinro](https://github.com/AlexxNB/tinro)
* [svelte-preprocess](https://github.com/sveltejs/svelte-preprocess)
* [postcss](https://github.com/postcss/postcss)
* [autoprefixer](https://github.com/postcss/autoprefixer)
* [normalize.css](https://github.com/necolas/normalize.css) (CDN in index.html)

Based on the official [Svelte template](https://github.com/sveltejs/template).
This will probably become obsolete after SvelteKit comes out, but I'll periodically 
update dependency versions until it is.

## Getting started

```
//You'll have to add #main until degit supports defaults other than master
npx degit kindoflew/svelte-starter#main <project-name>
cd <project-name>
npm install
npm run dev
```

Runs on localhost:5000

If you're making an SPA change "start" in package.json to:
```
"start": "sirv public --single"
``` 

