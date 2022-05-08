# Angular Electron Project Template
## https://www.c-sharpcorner.com/article/use-angular-application-as-desktop-application-using-electron/

ng new angular-electron-project

npm install electron@latest --save-dev

create main.js in root folder

add npm script
    "main": "main.js" to package.json
add npm script
    "desk": "ng build --base-href ./ && electron ."

To run web app
    ng serve
To run desktop app
    npm run desk