# summit.g0v.tw 2016

## Developmnet

### local setup

Install packages via `$ npm install` and run `$ npm start` to see `localhost:8080/2016/`

### git flow

You can use `git-flow` commands to create feature branches if you want.
Set gh-pages to production relase branch which is usually `master`.
And set `2016` to next release branch which is usually `develop`.
For the rest, give them your preferences.

## Static page generation

The following command builds the entire site within `/dist` directory, and generates static pages for SEO purpose.

```
$ npm run build
```

After this, you may:

```
$ npm run start:dist
```

And visit `http://localhost:3474/2016` to see the compiled site in action.

# License

MIT http://g0v.mit-license.org
