# Contribute to SerialPort!

Do you want to help out but don't know where to start?

## Guideline Contents

There are a lot of ways to get involved and help out:
- [Reporting an issue](#reporting-issues)
- [Requesting features](#requesting-features)
- [Submitting Pullrequests](#pullrequests)
- [Writing tests](#writing-tests)
- [Writing Documentation](#writing-docs)
- [Sample Projects](#sample-projects)

<a name="reporting-issues"></a>
## Reporting An Issue

SerialPort does it's [issue tracking](https://github.com/EmergingTechnologyAdvisors/node-serialport/issues) through github. To report an issue first search the repo to make sure that it has not been reported before.  If no one has reported the bug before, create a new issue and be sure to include the following information:

Operating System and Hardware:
NodeJS Version:
Serialport version:
Python Version (if you're having trouble building serialport):


**Operating System:** (e.g Windows, OSX, Linux)
**NodeJS Version:**
**SerialPort Version**
**Hardware you are having an issue with:** (e.g. arduino, another computer, etc)
**What your expectations are:**
**What the actual outcome is:**
**Steps to reproduce (including code samples):**

If the issue has been reported before but you have new information to help troubleshoot the issue, add a comment to the thread with the same information as requested above.


<a name="requesting-features"></a>
## Requesting Features
To request a new feature be added take a look at the [current roadmap](https://github.com/EmergingTechnologyAdvisors/node-serialport/issues/746) and create a [github issue](https://github.com/EmergingTechnologyAdvisors/node-serialport/issues) and include:

**What feature you'd like to see:**
**Why this is important to you:** (this is here because it's interesting knowing what cool things people are working on and also could help community members make suggestions for work-arounds until the feature is built)

<a name="pullrequests"></a>
## Submitting Pull Requests
To contribute code to SerialPort, fork the project onto your github account and do your work in a branch. Before you submit the PR, make sure to rebase master into your branch so that you have the most recent changes and nothing breaks or conflicts.  Lint and test your code using [grunt](https://github.com/gruntjs/grunt). Also squash your commits to a reasonable size before submitting.

All contributions must adhere to the eslint rules by maintaining the existing coding style.

If you are contributing code, it must include unit tests that fail if the working code isn't present and succeed when it is.

When contributing new features you must include documentation.

It's very important that your pull requests include all of the above in order for users to be able to use your code. Pull requests with undocumented code will not be accepted.

<a name="writing-tests"></a>
## Writing Tests

Tests are written using [mocha](https://mochajs.org/), [chai](http://chaijs.com/) and [sinon](http://sinonjs.org/).  If you are having issues making a test pass, ask for help in the SerialPort [gitter](https://gitter.im/EmergingTechnologyAdvisors/node-serialport) room.  Tests can be the hardest part to write when contributing code, so don't be discouraged.

<a name="writing-docs"></a>
## Writing Documentation

We are always looking to improve our docs.  If you find that any are lacking information or have wrong information, fix and submit a PR.  If you're looking for areas to start writing docs for, see the [docs](https://github.com/EmergingTechnologyAdvisors/node-serialport/labels/docs) label in issues.

We use [jsdoc](http://usejsdoc.org/) and [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown) to generate our docs. Make your changes to `.README.hbs` or the documentation blocks in the JavaScript files and run `npm run docs` to update `README.md`.

Docs should have tested and working sample code. Many people using SerialPort are learning how to work with hardware for the first time, so write for a beginner audience.

<a name="sample-projects"></a>
## Sample Projects

Have you made something cool with SerialPort? Is it part of your latest product? Let us know! There are a lot of people out there hacking on similar projects and looking for ideas, help or code. It's great to share!
