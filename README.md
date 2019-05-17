## maptalks-plugin-tpl-base

[![Greenkeeper badge](https://badges.greenkeeper.io/sakitam-gis/maptalks-plugin-tpl-base.svg)](https://greenkeeper.io/)

### use

This is a project template for maptalks-cli. It is recommended to use npm 3+ for a more efficient dependency tree.

```bash
$ npm install -g maptalks-cli
// list available templete
$ maptalks list
// generate project
$ maptalks init sakitam-gis/maptalks-plugin-tpl-base my-project
$ cd my-project
$ npm install
$ npm run dev
```

### options

| filed | params | desc |
| :--- | :--- | :---------- |
| `name` | `String` | package name |
| `homepage` | `String` | the project homepage |
| `namespace` | `String` | The lib namespace。 |
| `version` | `String` | The package version |
| `description` | `String` | The project description |
| `Author` | `String` | The project author |
| `scss` | `choices` | Use scss for your style code? |
| `ESLint` | `choices` | Use ESLint to lint your code? |
| `autoInstall` | `choices` | Should we run `npm install` for you after the project has been created?  |


Fork It And Make Your Own
You can fork this repo to create your own boilerplate, and use it with maptalks-cli:

```bash
maptalks init username/repo my-project
```
