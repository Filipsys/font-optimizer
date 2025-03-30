# font-optimizer
Font optimizer plugin for Vite to lower the size of font files getting sent to the client

### TODO:

- [ ] Create a Vite plugin, read through [Rollup documentation](https://rollupjs.org/introduction/) and the [Vite Plugin API](https://vite.dev/guide/api-plugin.html).
- [ ] Create a config file in the root directory of the project.
- [ ] Find the font files in the project.
- [ ] Check the used letters in the html files, possibly separate different pages.
- [ ] Get the font file format, read the file and create an optimized font file to the page, containing only the necessary letters.
- [ ] Have the option to pick from fonts, set font blacklists/whitelists, check HTML & CSS files for which font files are used, possibly create multiple files for viewports (what the user initially sees, the rest of the font will be loaded in after)

### Support font file types TODO:

- [ ] TTF
- [ ] OTF
- [ ] WOFF
- [ ] WOFF2
