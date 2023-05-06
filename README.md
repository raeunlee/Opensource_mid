# About me Page
단국대학교 '오픈소스SW활용 2분반' 중간고사 대체과제의 일환으로 자기소개 페이지 생성

### How to Build the project?
* `npm start` simple way to start the project!

#### npm Scripts
* `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
* `npm run build:assets` copies the files in the `src/assets/` directory into `dist`
* `npm run build:pug` compiles the Pug located in the `src/pug/` directory into `dist`
* `npm run build:scripts` brings the `src/js/scripts.js` file into `dist`
* `npm run build:scss` compiles the SCSS files located in the `src/scss/` directory into `dist`
* `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
* `npm run start:debug` runs the project in debug mode
* `npm start` or `npm run start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`

### Contact Form

The contact form available with this theme is prebuilt to use [SB Forms](https://startbootstrap.com/solution/contact-forms).
SB Forms is a simple form solution for adding functional forms to your theme. Since this theme is prebuilt using our
SB Forms markup, all you need to do is sign up for [SB Forms on Start Bootstrap](https://startbootstrap.com/solution/contact-forms).

After signing up you will need to set the domain name your form will be used on, and you will then see your
access key. Copy this and paste it into the `data-sb-form-api-token='API_TOKEN'` data attribute in place of
`API_TOKEN`. That's it! Your forms will be up and running!

If you aren't using SB Forms, simply delete the custom data attributes from the form, and remove the link above the
closing `</body>` tag to SB Forms.


## Copyright and License

Copyright 2013-2023 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-personal/blob/master/LICENSE) license.

