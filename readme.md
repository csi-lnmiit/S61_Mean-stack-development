# S61_Mean-stack-development
Tic Tac Toe
===========
1. Purpose
The main purpose of the project is to create an online application for the
Tic-Tac-Toe game, which we all enjoyed
playing as children. The game would allow real time game to be played between
two online users. The idea is to get
accustomed to the Javascript and glean more knowledge about the existing
frameworks and libraries of JavaScript like
AngularJS and ReactJS. It's a beginning project and we'll be using these
technologies for the first time.
At its core, webpack is a static module bundler for modern JavaScript
applications. When webpack processes your application,
it recursively builds a dependency graph that includes every module your
application needs, then packages all of those modules
into one or more bundles.
Babel is a tool for transpiling (compiling) ES6/ES7 code to ECMAScript 5
code, which can be used today in any modern browser.
Even more - Babel has extensions for transpiling JSX for React and Flow
syntax for static type checking.
It’s composed of various small modules. Out of the box, Babel doesn’t do
anything. It uses presets for compiling the code.
2. Technology Stack
a[0]: Javascript for Frontend and Backend
===========================================
FRONTEND
===========================================
a. React/Angular - based on out pace of picking up the framework
b. Webpack - module bundler
c. Babelrc - code transpiler
d. CSS / Styled-components
e. HTML for Structure
===========================================
BACKEND
===========================================
f. NodeJS for socket programming
3. Future Prospect of the project
- This project aimed at building only the tic tac toe web application but it
can be applied to develop other real-time games such
as Monopoly, Uno etc. The game can be extended to be used as a multiplayer
application. Also, the same technology can be used
create a chatting application with multiple users. With the increased number
of users and increased complexity of this game
application, some new libraries may be needed.
4. Dependencies
-Babelrc
-Webpack
-React
-Angular
5. Directory Structure
/--components/*.js
-- import utils and helpers here, contains business logic
/--styles/*.css
-- contains styling rules
/--utils/*.js
-- generic methods which are independent of business logic, similar to
helpers/--helpers/*.js
-- components' helper functions
/--package.json // this file contains metadata
--
/--.eslintrc // contains linting syntax
-- editor plugin, rules for writing javascript code - linter
/--webpack.config.js // contains the config for code bundling
-- configurations for code bundling
/--.babelrc // contains the config for code transpiling
