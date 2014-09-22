gulp-uglifycss
==============

Gulp plugin to use [UglifyCSS](https://github.com/fmarcia/UglifyCSS).

[![Build Status](https://magnum.travis-ci.com/rezzza/gulp-uglifycss.svg?token=SSZ9gxnSGfss4494CX5W)](https://magnum.travis-ci.com/rezzza/gulp-uglifycss)

## Install

```
npm install gulp-uglifycss
```

## Usage
```javascript
var uglifycss = require('gulp-uglifycss');

gulp.task('css', function () {
  gulp.src('./styles/**/*.css')
    .pipe(uglifycss({
      max-line-len: 80
    }))
    .pipe(gulp.dest('./dist/'));
});
```

## Options

No specisific options. You can use all the [UglifyCSS](https://github.com/fmarcia/UglifyCSS) options.
