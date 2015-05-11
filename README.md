# gulp-contrib-copy
Gulp: Copy files from source to destination <br>

## Installation
```javascript
npm install gulp-contrib-copy --save-dev
````

## Usage
```javascript
var copy = require('gulp-contrib-copy');

gulp.task('copy', function() {
	gulp.src('src/**/*')
		.pipe(copy())
	    .pipe(gulp.dest('dest/'));
```

## Errors

`gulp-contrib-copy` emits an 'error' event if it is unable to copy a specific file.

To handle errors across your entire pipeline, see the
[gulp](https://github.com/gulpjs/gulp/blob/master/docs/recipes/combining-streams-to-handle-errors.md#combining-streams-to-handle-errors) documentation.

## Note
`This package is process of being created. Please be patient. Feel free to contribute if you like.`