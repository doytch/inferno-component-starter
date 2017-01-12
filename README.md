# inferno-component-starter
Boilerplate for creating an inferno-component intended for NPM.

##Tools Used
- **webpack** for building.
- **babel** w/ ES2015, stage-2 and Inferno presets.
- **eslint** w/ customised AirBnB ruleset.
- **mocha** and **chai** for testing.

##Usage
- Clone this repo.
- Update the `package.json` and `README.md` with info about you and your new package.
- Write your components and put them in the `src` directory.
- Re-export them from `src/index.js`
- `npm run build` puts the built bundle into `lib`.
- `git add --all .` and `git commit`
- `npm publish`
- Make changes...
- `npm version <major|minor|patch>`
- `npm publish`

```
