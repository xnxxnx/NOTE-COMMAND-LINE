## Some Basic NPM Command

npm documents : [docs.npmjs.com](https://docs.npmjs.com/)

- `npm -h` Get npm help
    * `npm <cmd> -h` get detail about that specific <cmd> 
    * `npm help <cmd>` get help documents about <cmd>

- `npm init` create package.json
    * `npm init -y` create package.json with all default answers answered as YES.
    * `npm set init-author-name name` set init autor name

- `npm install`
    * `npm i packageName --save` / `npm i packageName -S` install package as dependencies (need in production)
    * `npm i packageName --save-dev`/ `npm i packageName -D` install package for development env
    * `npm i packageName -g` install package globally so that you can use command line on it
    * `npm i packageName@verison` install specific verison
    * `npm i packageUrl` install package by url

- `npm uninstall packageName`
    * `npm uninstall packageName --save` remove package from dependencies
    * `npm un` / `npm rm`

- `npm list` check installed packages with their related packages
    * `npm list --depth 0` check packages intalled by yourself
    * `npm list --depth 1` check first level packages
    * `npm list --depth 0 --long true` detail about installed packages
    * `npm list --global true` check global packages

- `npm search`
- `npm i npm@latest -g` update npm