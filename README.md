npm init -y (create a new project)
node -v
npm - v
npm i -D prettier
install the prettier extension
settings -> format on save
settings -> require config
create .prettierrc file in the root
npm i -D eslint eslint-config-prettier
//ESLint to find syntax or style errors before execution, creates the eslintrc configuration file, and /////installs the eslint-config-prettier to ensure that linter isn't overlapping with the tasks that Prettier is performing.
npm i -D parcel-bundler
npm i react react-dom
install npm intellisense extension
//remember to run npm install if moving forward in /////commits
npm install -D babel-eslint eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react
//babel is the transpiler
//helps eslint and babel work together
//a11y is accessibility
//make sure the eslint extends prettier rules are last int the eslintrc file as they just turn stuff off

anthing that can go on a right side of an assignment in javascript is an expression and can be used in {}

npm i -D eslint-plugin-react-hooks

//parentheses in the arrow function signify an //// ///implicit return compared to using {} which requires you type return

//Reach router better at accessibility than react router

npm install -D babel-eslint @babel/core @babel/preset-env @babel/plugin-proposal-class-properties @babel/preset-react

//babel transpiles the javascript

a + infront of a string variable turns it into a number instead of doing an number conversion


//this inside an arrow function will be this where it was written as opposed to a function using this which this is where it is being invoked