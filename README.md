# Booking.com Blog

## Decisions on front-end development

### HTML

 - [BEM](http://getbem.com). We're using it;
 - [HTML5](http://www.w3.org/TR/html5/). We're Using it;

### CSS

 - [BEM](http://getbem.com). We're using it;
 - [Sass](http://sass-lang.com). We're using it;
 - Based on the data of the current blog, we are supporting [IE10](https://en.wikipedia.org/wiki/Internet_Explorer_10)+;
 
 ---
 
## What you need to run this project

In order to run all tasks and be able to work in the project you need to have this installed in your local machine:

- [NodeJS](https://nodejs.org/); 


## Setup project

1. Clone the repository into your machine;
2. Go to project folder using your command line tool (`Terminal.app` for example.);
3. Run `npm install` to install development dependencies;
4. Run `gulp` to compile files;

Styles are in `sass/` folder.  
Running `gulp` task all styles will be compiled to `css/`.  

Since we're using [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer) you can write your CSS without be worried with browser prefix like `-moz` or `-webkit`. The gulp task will add all necessarie prefixes to your styles when compile them. :thumbsup:

---

## Compile to production

To do.