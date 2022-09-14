# typescript_project_template

thanks to:

https://javascript.plainenglish.io/a-beginners-guide-to-creating-a-typescript-starter-project-6129deeeb973

# instructions

`npm init -y`

? `sudo npm install -g yarn` todo: not works without `sudo`

? `sudo chown -R $USER /usr/local/lib/node_modules`

`yarn add @babel/core babel-preset-env babel-loader --dev`

`yarn add webpack webpack-cli --dev`

`yarn build`

TODO: remove --ignore-engines

`yarn add html-webpack-plugin --dev --ignore-engines`

`yarn add webpack-dev-server --dev --ignore-engines`

`yarn serve`

`yarn add typescript --dev`

`yarn add ts-loader --dev`

# Tools

## Prettier

`yarn add --dev --exact prettier`

check

`yarn prettier --write .`

##### prettier-vscode
```
"editor.formatOnSave": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
```

