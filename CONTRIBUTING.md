# Contributing

All contributions are welcome! To contribute to this project, create a branch off of 
`main`. Once your work is complete, submit a pull request. The project maintainers will 
look over your changes. Once your changes have been approved, they will be merged and 
deployed to the production site.

Before contributing, make sure to read our [README.md](README.md) as well as the 
[style guideline](https://github.com/tmdict/tmdict/blob/main/data/content/page/tmdict/about/about.en.md#style-guildeline), 
before submitting a pull request make sure you have tested your work following the setup instructions.

If you have questions, feel free to reach out to us over at https://www.tmdict.com/contact/.

## Navigation

- `data/`: Site content, texts, translations, images, etc.
- `etc/`: Miscellaneous files.
- `src/`: Source code.

## Useful Commands

- `npm run build`: Generates the entire site, saves output to `dist/`.
- `npm run build:dev`: Same as `npm run build`, all links are generated with `.html` extension.
- `npm run clean`: Cleans up projects.
- `npm run compile`: Compiles source code.
- `npm run dev`: Generates the entire site and starts a server (same result as `npm run build:dev` + `npm run start`).
- `npm run dev:book`: Generates `tmdict.com/book/` and starts a server.
- `npm run dev:chaldea`: Generates `chaldea.tmdict.com` and starts a server.
- `npm run dev:tmdict`: Generates `tmdict.com` and starts a server.
- `npm run start`: Starts a server to view the generated site in `dist/`, accessible at `http://localhost:8080/` in a browser.
