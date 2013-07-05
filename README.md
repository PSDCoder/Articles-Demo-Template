Articles-Demo-Template
======================
Template for demos with customization ability.

* Installation:
    1. We need Node.JS
    2. Install GruntJS. Instruction at [article on main website](http://gruntjs.com/getting-started).
    3. npm install.

* Basic usage:
    1. For create new page we must copy articles/dummy folder as template to articles folder with new name "SOMENAME".
    2. Add to gruntfile.js to recess:articlesFiles task new file: 'articles/SOMENAME/styles.css': 'articles/SOMENAME/less/styles.less'.
    3. Change some variables in 'articles/SOMENAME/less/variables.less' for customizew theme.
    4. Add some demo content to 'articles/SOMENAME/index.html'
    5. Build with command: grunt from console

    **You may use grunt watch for developing new demos. More at [Watch grunt plugin](https://npmjs.org/package/grunt-contrib-watch).
    Using: grunt watch
