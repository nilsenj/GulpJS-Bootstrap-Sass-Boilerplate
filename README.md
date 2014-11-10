
 > 
 Bootstrap + Gulp.js Boilerplate
======

#####Bootstrap | Gulp.js | jshint | coffee | sass | concat | uglify | rename | watch | connect | livereload


It is done with a help of Ruby & Sass and Node.js


## Getting Started


First, clone the repo, then 
~~~
you need to install Ruby  http://www.ruby-lang.org/en/downloads/
~~~

Second, install Ruby - Sass http://sass-lang.com/download.html
~~~
well-done
~~~


Then, to start compiling, just run in the root repo folder
~~~
npm install
~~~

**and**

then run in terminal
~~~
gulp
~~~
That's it!

### The details

Non-compiled Scss goes in **assets/stylesheets/**. These must be Scss.

Non-compiled Coffeescript goes in **assets/coffeescripts/**. These must be Coffeescript.

If you chose to use JS & Coffeescript, or are including libraries in JS, they go in **assets/javascripts/**. Here live the compiled Coffeescript files. They get linted an concatenated from here.

All compiled assets go to **dist/**. This includes a non-minified JS file, and a minified one. This also includes whatever Scss files in **assets/stylesheets/**. I recommend keeping a **main.scss** file that uses `@import` to import Scss partials (instead of having multiple Scss files).

It also has Livereload. Install the Chrome Extention here: https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en



Thanks to **everyone who is envolved** and a lot of people for this job I'm really happy to have Gulp.js and I hope that this simple Boilerplate will help you .
https://vk.com/idnikolenko


==============
