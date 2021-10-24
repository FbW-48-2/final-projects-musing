# Final Projects

Find here some orga suggestions & resources that might support you in your upcoming team coding experience.

## Teacher Meetings

- 30 (max 40) minutes per team
- Team meeting priority
- Once served - maybe no followup!
- Exception: Still free slots before lunch

## Tech Stack

Following some notes on Node Version and Libraries to safe in advance you from as much pain as possible :)

### Node Version

Most important: Use the same Node MAJOR Version for the whole backend / frontend team.

Why?

A lot of libraries depend on a certain Node major version to function properly. In case we use different major version, we can get into the nasty scenario, that for some folks a library works in their project, but for others the very same project code will produce super strange errors!

Therefore it is important to align our Node versions to prevent these very unpleasant scenarios :)

Example version: 15.14.0 => MAJOR Version is: 15, MINOR Version is: 14, PATCH Version: 0 

How to switch between Node Version easily?

#### NVM

With NVM (Node Module Manager) you can easily install & switch your Node version from the terminal like this:

`nvm install 15` // install latest version 15
`nvm use 16` // switch to another installed node version 16

Install Notes: https://github.com/nvm-sh/nvm

Just little note: Whenever you switch the node major version, you need to re-install global packages (like nodemon, live-server, jest, etc)! Global packages are installed separately for each Node Version on your system (to prevent conflicts).

So in case you wanna run "nodemon" on your terminal after you switched the version, don't panic if it tells "could not find 'nodemon'. Just re-install it :)


#### Backend & Frontend node version

The backend team can have a different Node Major version than the frontend team. That is alright. 

But all members which work on the SAME code base / repository, must use the same node major version to prevent unresolvable conflicts.


### Libraries

- Same UI Library for everyone please!
- Vanilla JS libs only when there is no React alternative
- Minimum: Feasability test of libs


## Coding orga

- Folder structure: Discuss & keep it!
- Try to avoid working on same files
- Pick a Git Merge strategy (e.g. GitHub Flow)
- First merges ideally together
- Deploy backend early!


## Resources

### API Connect Guide

Find how to do REST calls against your backend from React and how to process the result in your state:

https://github.com/losrobbos/api-connect-guide

### Data Modeling 

Samples for some common data models: https://github.com/losrobbos/data-modeling-guide

Will get updated from time to time with new stuff.

### File Upload 

File-Upload guide: https://github.com/losrobbos/file-upload-guide

The guide has two branches. One with base64 encoding, for storing smaller files (like images)

And another branch (multer-form-data) which shows how to upload raw binary data to the backend (which fits better for uploading bigger files, like video)

### Deployment 

Vercel Deploy Guide: https://github.com/losrobbos/vercel-deploy-guide
Heroku Deploy Guide: https://github.com/losrobbos/heroku-node-deploy-guide

### Git Team Branching & Merging

The simple GitHub flow guide for teams: https://github.com/losrobbos/github-flow-guide

### App Development for Smartphone

React Native Guide: https://github.com/losrobbos/react-native-guide

### Prototyping

Prototyping is a nice technique for medium to bigger projects to integrate frontend & backend and get a first running fullstack app as EARLY and hassle-free as possible, before actually implementing all the details.

API Prototyping: https://github.com/losrobbos/api-prototyping

### Glossary 

Nice Dev Glossary from DCI about common JS WebDev terminology: https://github.com/losrobbos/glossary

