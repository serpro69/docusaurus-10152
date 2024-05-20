Repo to reproduce https://github.com/facebook/docusaurus/issues/10152

Steps:

- clone repo
- run `npm run start`
- open [foo](http://localhost:3000/docs/foo) page in the browser
- click on `bar` link

Result: link leads to `http://localhost:3000/docs/bar.md` instead of `http://localhost:3000/docs/bar`
