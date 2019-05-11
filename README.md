# dev-vanilla-js-template

This sets out basic web files as a template for a new web project.

Note that to use chrome dev tools and ES6 export and import you must declare the index.js (top .js file) using a type of "module" and not the usual "text/javascript".

````jsut before <\body> in html:   <script type="module" src="./index.js"></script>````

It is not necessary to declare the imported .js files (e.g. kexport.js, lexport.js).

Finally you must use the express web server to display the data in the browser and not file:///path/index.html
