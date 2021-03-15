Check for node and yarn version is there
node --version

yarn --version

Install after node and yarn are confirmed

yarn global add @vue/cli

to create a project 
npx @vue/cli@4.4.6 create linting-with-vue

when asked  to pick a preset just hit enter for default

Go to the package.json and look for the "extends" key

Install an extension Vetur by Pine Wu
Install an extension ESLINT by Dirk Baeumer

ctrl + ,   to open up setting go to workspace and in the search type vetur, scroll all the way down until you seel validation for script, style and template are checked

