## Tooling

• NPM - Node (Compiler language in Jscript)
• Prettier
• ESLint

## Back-end (Local filesystem architecture)

• This v1 focuses on writing data to files in CVS

## Front-end (React)

• Basic functionality is to allow the creation of goals, visualization of them, saving to file, in order to look at data patterns.

# Algorithm for creating this application

## (Commit One)

1. Create a repository at root directory
   a) Run : git init (Assumes that git is installed from terminal)
   b) Create .gitignore file, and add 'node_modules'
2. Create NPM project (Need to have node installed)
   a) npm init
3. Enable Prettier—Code formatter
   a) npm i -D prettier
   b) Create an .prettierrc file & add {} to enable default configuration
   c) Install prettier plug-in at Visual Studio Marketplace
   d) Add a package.json script to manually run prettier (Optional)
4. Install ESLINT- Code refactor
   a) Run npm i -d eslint eslint-config-prettierxw
   b) Run : npx eslint --init
   c) Install eslint plug-in at Visual Studio Marketplace
5. Link Prettier and Eslint
   b) Add Prettier to extends option in .eslintrc.json
