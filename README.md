![MIT LICENSE](https://img.shields.io/github/license/scottbromander/the_marketplace.svg?style=flat-square)
![REPO SIZE](https://img.shields.io/github/repo-size/scottbromander/the_marketplace.svg?style=flat-square)
![TOP_LANGUAGE](https://img.shields.io/github/languages/top/scottbromander/the_marketplace.svg?style=flat-square)
![FORKS](https://img.shields.io/github/forks/scottbromander/the_marketplace.svg?style=social)

# Github_Greenlight

## Description

_Duration: One Afternoon_

This program makes and commits changes to github on a timer.  It does this by starting a cronjob that executes terminal commands.  These will cause another program to rewrite itself and then commit those changes to github.  This means you could have any number of commits in github that you like or just keep your github eternally greenlit.

This program is meant as a proof of concept and conversation piece.  I do not intend to run this beyond this project.  I just want it to be something interesting that people might notice and dig a little deeper, maybe talk about in interviews. 

## Screen Shot

Include one or two screen shots of your project here (optional). Remove if unused.

### Prerequisites

Link to software that is required to install the app (e.g. node).

- [Node.js](https://nodejs.org/en/)

## Installation

1. Fork and Clone the repo.
2. Open up your editor of choice and run an `npm install`
3. Run `node index.js` in your terminal

## Usage

1. Run the program with 'Node index.js'
2. The Cronjob will start and depending on what your timer is set for (default 1 minute) it will push a change to github. I wouldn't run it faster than a minute to avoid command conflicts.  (https://www.npmjs.com/package/cron)
3. Keep it running until you have the desired number of commits in your github.



## Built With

1. Javascript
2. Cronjob
3. Child_process
4. Chalk
5. Clear
6. Figlet

## Future

I have a number of different ideas for how this could be expanded.  I could use a CLI and the github API to link your github and create a new repository for this.  I could use a CLI to perhapts set the Cronjob when you start it up.  I could try to make this a .app so you can run it on startup.  Lots of potential avenues.

## License
[MIT](https://choosealicense.com/licenses/mit/)

_Note, include this only if you have a license file. GitHub will generate one for you if you want!_

## Acknowledgement
1. This tutorial was really interesting and even though I ended up not using the Github API and a CLI,  it would probably be where I brought the project next. (https://www.sitepoint.com/javascript-command-line-interface-cli-node-js/)
2. User Patrick Roberts for his code in this thread.  It was invaluable in creating something that rewrites itself. (https://codegolf.stackexchange.com/questions/107642/permanently-self-modifying-code)

## Support
If you have suggestions or issues, please email me at [evantilton@gmail.com](www.Etilton.com)