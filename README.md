# :star2: Stargazers :star2:
 Welcome to Stargazers! This is a one-page demo of html and css that shows different places to find great stars to look at the night sky.

 ## :construction: Dependencies :construction:
 - Node v11.6.0
 - `"browser-sync": "^2.27.4"`
 - `"node-sass": "^6.0.1"`
 - `npm-run-all`


 ## :wrench: Let's Begin :wrench:
 1. Make sure you have [Node.js](https://nodejs.org/en/download/) installed on your machine.
 2. Ensure you are using at least v11.6.0 for this project.
 3. Navigate to your project folder in the terminal.
 4. Run `npm install` to install all other dependencies from the `package.json` file.
 5. Run `npm run build`. This will copy all the necessary files to the build directory.
 6. For a live refresh environment, use `npm start`


## :thought_balloon: Rationale :thought_balloon:
- HTML is in standard document format with BEM class naming convention. I use BEM because it easily organizes where you are within an element and eliminates the need to rely heavily on broad specificity rules for specific elements.

- CSS is using Sass where `styles.scss` is used for imports, `global.scss` is used for universal styles, `vars.scss` and `mixins.scss` are used respectively and `type.scss` is used for all type rules and then from there the files are broken out by element.
  - I use variables as a way to master control rogue styles. I see it as my master list of values that I keep track of in one spot (ah, the beauty of Sass). Another rule of thumb is if I use it twice (or think I will in any future instance), it should be a variable.

  - I use mixins as a step up from variables for that same master control but with blocks of code. In this project, I also used it for various responsive setups.
