# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

#1. ng build --prod --output-path docs --base-href https://wenchaoweng.github.io/my-app/
#2. 当构建完成时，把docs/index.html 复制为 docs/404.html
#3. 提交整个docs文件夹到github上
#4. 在 GitHub 的项目页中，把该项目配置为从 docs 目录下发布。
#5. 前往https://wenchaoweng.github.io/my-app/查看部署好的页面。