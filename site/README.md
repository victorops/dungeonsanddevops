## Contents
1. Summary
2. Resources
3. Workflow
***
### Summary
This is a "create your own adventure game" built w/ Twine. Targeted users of the game are VictoprOps Customers.

The game is manually published in Twine to HTML so it can be served by Netlify. There's a link between Netlify and the Github repo [dungeonsanddevops](https://github.com/victorops/dungeonsanddevops). Whenever there's an update to the master branch, Netlify will deploy the contents in site/public (see netlify.toml).

### Resources
- [Twine](https://twinery.org/)
- [Harlowe](https://twine2.neocities.org/)
- [Netlify](https://app.netlify.com/sites/victoropsadventure/overview)
- [Deployed Site](devopsgame.victorops.com)

### Workflow
1. Create a branch off master
2. Make changes to site/devopsgame.html in Twine
3. Publish site/devopsgame.html in Twine and put the output file in site/public/devopsgame.html
4. Preview changes locally
5. Merge working branch back into master
6. Check that the deployment went ok in Netlify



