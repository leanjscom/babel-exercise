# Babel exercise

The goal of this exercise is to understand some basics of Babel.

## Get started

If you have yarn:
`git clone git@github.com:leanjscom/babel-exercise.git && cd babel-exercise && yarn install`

If you have npm:
`git clone git@github.com:leanjscom/babel-exercise.git && cd babel-exercise && npm install`

## Exercise

- Run this command **`node index.js`** and you'll see an error. Where is the problem?
- Run this command **`npm install --save-dev babel-cli babel-preset-es2015 babel-preset-stage-2`**
- You should configure babel using the presets in the .babelrc file. Let's add the following presets:
**`{
  "presets": ["es2015"]
}`**
- If this is working you should be able to see the transpiled code by running: **`babel index.js`**
- Now you can use the -o flag to output this into a file: **`babel index.js -o transpiled_index.js`**
- Now you should be able to run the transpiled file by running: **`node transpiled_index.js`**
- More questions? Don't forget to check out the docs, in particular: http://babeljs.io/docs/usage/cli/
