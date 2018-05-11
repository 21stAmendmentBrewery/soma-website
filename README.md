# SOMA BEER Co.
SOMA BEER Co. located in San Leandro, CA.

Website is built with:
### Victor Hugo


### Netlify CMS
You will need to replace your
[Docs](https://www.netlifycms.org/docs/)

#### Setup
You will need to replace repo with your repo in the site > static > admin> config.yml

```yaml
backend:
  name: github
  repo: kungfukoala/_underscore # Replace with your repo
  branch: master
```

### LostGrid
[Get Started](https://github.com/peterramsing/lost)
[Docs](http://lostgrid.org/docs.html)

### POSTCSS variables
[Docs](https://www.npmjs.com/package/postcss-css-variables)

### POSTCSS Colour functions
[Docs](https://www.npmjs.com/package/postcss-colour-functions)


## Usage

### Prerequisites

You need to have the latest/LTS [node](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/get-npm) versions installed in order to use Victor Hugo.

Next step, clone this repository and run:

```bash
npm install
```

This will take some time and will install all packages necessary to run Victor Hugo and it's tasks.

### Development

While developing your website, use:

```bash
npm start
```

or

```bash
gulp server
```

Then visit http://localhost:3000/ *- or a new browser windows popped-up already -* to preview your new website. BrowserSync will automatically reload the CSS or refresh the whole page, when stylesheets or content changes.

### Static build

To build a static version of the website inside the `/dist` folder, run:

```bash
npm run build
```

To get a preview of posts or articles not yet published, run:

```bash
npm run build-preview
```

See [package.json](package.json#L7) or the included gulp file for all tasks.
