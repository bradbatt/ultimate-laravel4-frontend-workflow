### The Ultimate Laravel 4 + Bootstrap 2 or 3 + GruntJS with LiveReload

#### How to use - instruction
1. Copy all the files and folders to the root directory of your Laravel 4 project.
2. Run `$ npm install` (or `$ sudo npm install` on Linux or OSX) from the root of your project. This will install all the required dependancies.
3. Run `$ grunt build-bs2` or `$ grunt build-bs3` to build the inital bootstrap 2 or 3 files, stylesheets and scripts.
3. Next add the stylesheets and scripts below to your project. NOTE: The last script 'livereload.js' is only optional if you already have the livereload plugin already installed for Chrome/FireFox !!
4. Finally: Run `$ grunt watch:bs2` or `$ grunt watch:bs3` depending on which version of Bootstrap you want to use to start watching for file changes. If a change occurs livereload will kick in and update your browser.
5. All done! You can edit any of your Laravel view files, Bootstrap 3 LESS, CSS or JS files, and livereload should kick in.

#### Helpers

To start watching files at any time, simply run the command `$ grunt watch:bs2` or `$ grunt watch:bs3` from the root of you project.

To end the watching of file press CTRL+C or cmd+c.


#### Stylesheets & Scripts
`<link rel="stylesheet" href="assets/css/bootstrap.min.css">`

`<link rel="stylesheet" href="assets/css/jquery-ui.min.css">` (Optional!)

`<script src="assets/js/jquery-1.9.1.min.js"></script>`

`<script src="assets/js/bootstrap.min.js"></script>`

`<script src="assets/js/jquery-ui-1.10.3.min.js"></script>` (Optional!)

`<script src="http://localhost:35729/livereload.js"></script> `

NOTE: The last script 'livereload.js' is only optional if you already have the livereload plugin already installed for Chrome/FireFox !!