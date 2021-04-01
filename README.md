# svelte-starter

A basic Svelte boilerplate with:
* [rollup](https://github.com/rollup/rollup)
* [tinro](https://github.com/AlexxNB/tinro)
* [svelte-preprocess](https://github.com/sveltejs/svelte-preprocess)
* [postcss](https://github.com/postcss/postcss)
* [autoprefixer](https://github.com/postcss/autoprefixer)
* [normalize.css](https://github.com/necolas/normalize.css) (CDN in index.html)

Based on the official [Svelte template](https://github.com/sveltejs/template).

I'm going to keep this around for awhile because I believe the official template might be deprecated soon and it's nice to have a no-setup boilerplate for fast prototyping, etc.

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

