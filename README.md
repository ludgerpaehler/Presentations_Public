<h1 align='center'>Index of Presentations</h1>

***

Public Repository of Presentations in [reveal.js](https://revealjs.com), and doubled on the [webpage](https://ludger.fyi/presentations).

## Usage Instructions

To create a new presentation create a new branch, on which the template is then to be copied into a directory for the talk. To begin, the submodule is to be updated

```bash
git submodule update --init --recursive
```

`package.json`, and `gulpfile.js` from the `reveal.js` directory are then to be copied into the folder for the talk. This is then to be npm-installed

```bash
npm install
```

After which we can start the server to edit the slides

```bash
npm start
```

Once the slides are completed a PR is to be opened to later be merged into `main`.

