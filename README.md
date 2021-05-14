## How to convert existing Angular project (10.1.0) to ESLint

ng new angular-eslint-migration -- 11.2.10

## https://dev.to/gsarciotto/migrating-and-configuring-eslint-with-angular-11-3fg1

## https://www.youtube.com/watch?v=SydnKbGc7W8&t=346s

ng add @angular-eslint/schematics
ng g @angular-eslint/schematics:convert-tslint-to-eslint {{YOUR_PROJECT_NAME_GOES_HERE}}

"extends": [
"plugin:@angular-eslint/recommended",
"eslint:recommended",
"plugin:@typescript-eslint/recommended",
"plugin:@typescript-eslint/recommended-requiring-type-checking",
"plugin:@angular-eslint/template/process-inline-templates"
],

npm install -D prettier eslint-config-prettier eslint-plugin-prettier

## Check in .vscode/settings.json (C:\Users\I28298\AppData\Roaming\Code\User)

{
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"editor.formatOnPaste": false
}

# Ignore artifacts:

## package.json -

{
"name": "prettier-config-example",
"scripts": {
"format": "prettier --write 'projectA/_.js' 'projectB/_.js'" ,tsx}'
},
"devDependencies": {
"prettier": "1.18.2"
}
}
