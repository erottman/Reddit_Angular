
mkdir my-project
cd !$
yarn init -y
yarn add --dev lite-server
yarn add angular@1.6.0

create index.html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <script src="/node_modules/angular/angular.min.js"></script>
  </body>
</html>

package.json
{
  "name": "reddit-clone-solution",
  "version": "1.0.0",
  "author": "Galvanize <info@galvanize.com>",
  "license": "MIT",
  "scripts": {
    "start": "lite-server"
  },
  "devDependencies": {
    "lite-server": "^2.2.2"
  },
  "dependencies": {
    "angular": "1.6.0"
  }
}



Install the app by running `yarn`
yarn install

Run the app with `npm start
