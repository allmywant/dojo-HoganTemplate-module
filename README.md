dojo-HoganTemplate-module
=========================

Translating <a href='https://github.com/twitter/hogan.js'>hogan.js</a> into dojo module so that we can use it by require function.
For example:

require("./HoganTemplateEngine", function(hogan){
   hogan.compile(templateString);
   hogan.render({/* javascript data object */});
});
