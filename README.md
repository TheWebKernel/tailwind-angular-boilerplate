# TailwindBolerplate

Used @angular-builders/custom-webpack for compiling

Tailwind config `tailwind.config.js`

Tailwind css entry `src/tailwind.scss`


Change in `angular.json` config

```...
    "architect": {
        "build": {
            "builder": "@angular-builders/custom-webpack:browser", // ←
            "options": {
            "customWebpackConfig": {            // ←
                "path": "extra-webpack.config.js" // ←
            },                                  // ←
            // ...
            "styles": [
                "src/tailwind.scss",              // ←
                "src/styles.css"
            ],
            // ...
            }
        },
        "serve": {
            "builder": "@angular-builders/custom-webpack:dev-server", // ←
            "options": {
            "customWebpackConfig": {            // ←
                "path": "extra-webpack.config.js" // ←
            },                                  // ←
            // ...
            }
        }
    }
    ...

```


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).



### For any query contact sing [bphkns@gmail.com](mailto:bphkns@gmail.com) or [maxyspark@gmail.com](mailto:maxyspark@gmail.com)
