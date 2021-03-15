https://technicallyfletch.com/how-to-setup-eslint-and-prettier-with-vscode-and-vuejs/

Check for node and yarn version is there
node --version

yarn --version

Install after node and yarn are confirmed

yarn global add @vue/cli
or
npm install -g @vue/cli

to create a project theres to ways to do this, the command line way is easier but vue UI will give you more analitic and you can start and stop your server from the browser.
For command line:
vue create app-name
or
npx @vue/cli@4.4.6 create linting-with-vue

For the UI set up:
vue UI
Works as a project manager.

when asked  to pick a preset just hit enter for default

Go to the package.json and look for the "extends" key

Install an extension Vetur by Pine Wu
Install an extension ESLINT by Dirk Baeumer

ctrl + ,   to open up setting go to workspace and in the search type vetur, scroll all the way down until you seel validation for script, style and template are checked

