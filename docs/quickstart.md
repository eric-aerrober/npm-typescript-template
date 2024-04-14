# Get started with this template

First create a new github repository. Lets call it `my-new-package`.

Then clone this into your local machine:

```
git clone https://github.com/eric-aerrober/npm-typescript-template
```

And remove the git history, replace the remote url with your new repository

```
rm -rf .git
git remote set-url origin https://github.com/my-username/my-new-package
```

Then replace all the references over, this will require edits to the following files:

- README.md
- package.json
- LICENSE
- docs/_coverpage.md
- docs/index.html

Then install the dependencies:

```
npm install
```

## Additional GitHub setup

1. Add a new secret to your repository called `NPM_TOKEN` with your npm token.
2. Go into settings -> github pages and set the source to `main` branch and `/docs` folder.