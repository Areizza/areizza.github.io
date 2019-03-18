**Display Default Create React App as a GitHub Page**
 
_This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app)._
  >Link: [testReactApp](https://areizza.github.io/testReactApp)


**What did I learn?**
- Add homepage property in `package.json` with appropriate link and add scripts to deploy
  ```
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build"
  ```
  >_Don't forget to `npm install gh-pages`!_
- A production build of the app is needed to deploy it to GitHub Pages :shipit:
  (reads index.html, otherwise will only show the README.md)
  ```
  npm run deploy
  ```
  >_Make sure that there are the necessary scripts!_
- The built app code is contained in the `gh-pages` branch :exclamation:

  >_Any other branch can be used for the working code!_
- Add node_modules to `.gitignore` !!! :+1:

  >_Avoid committing a huge folder full of code!_


**Next steps?**
- [ ] :star2: Finish designing portfolio site layout 
- [ ] :sweat_drops: Test in this testReactApp repository
- [ ] :muscle: Implement design in new create-react-app and test locally
- [ ] :confused: Figure out where to host media files
- [ ] :wrench: Build production build and upload to new repository for portfolio site
