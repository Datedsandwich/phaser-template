### Phaser Project Template
This repository is here to allow me to more quickly get up and running with Phaser. It's got all of the set up that I am used to for building and transpiling ES6.

#### Instructions
To get set up, run `npm install` in the root directory.

To run the game with hot reloading, run `npm run dev`

To build the game, run `npm run build`

You can format the project by running `npm run format`, this will also run on any changed .js files as a pre-commit hook.

##### Deployment
To deploy as a GitHub Pages page, build the game and commit the build to a new branch. Then run `npm run deploy`, which will push it up to GitHub.

You can then delete the branch with the built artefact.