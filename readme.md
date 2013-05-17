### The Ultimate Laravel 4 + Bootstrap 3 + GruntJS with LiveReload

#### How to use - instruction
1. Copy all the files and folders to the root directory of your Laravel 4 project.
2. Run $ npm install (or sudo npm install on Linux or OSX) from the root of your project. This will install all the required dependancies.
3. Add the following stylesheets and scripts to your projects view files.

<link rel="stylesheet" href="assets/css/bootstrap.min.css">
<link rel="stylesheet" href="assets/css/jquery-ui.min.css">
<script src="assets/js/jquery-1.9.1.min.js"></script>
<script src="assets/js/bootstrap.min.js"></script>
<script src="assets/js/jquery-ui-1.10.3.min.js"></script> (OPTIONAL!!)
<script src="http://localhost:35729/livereload.js"></script> (Only optional is you already have the livereload plugin already installed for Chrome/FireFox)

4. Run $ grunt watch:bs3
5. All done! You can edit any of your Laravel view files, Bootstrap 3 LESS, CSS or JS files, and livereload should kick in.

