                                                           JAVASCRIPT OPTIMIZATION TRICKS
                                                              
       -----------------------------------------------------------------------------------------------------------------------------
        1.Order in which elements are loaded
          ->First, it’s important that all elements in the <head> section are pre-loaded, before the visitor sees anything in-browser,
             then all subsequent elements are ordered to load in a logical way. Any JavaScript inside the <head> section can slow down 
             a page’s rendering.
         
        2.Optimize Javascript with minification
          ->Optimization is a special type of JavaScript minification. These kind of minimizers not only delete unuseful white spaces, 
            commas, comments etc. but also help to avoid “dead code”:
            * Google Closure Compiler
            * UglifyJS
            * Microsoft AJAX Minifier
          
        3.Use the HTTP/2 protocol
          ->This second, encrypted version of the main Internet protocol can provide you with a lot of cool features, including the 
          asynchronous download of external files, most notably JavaScript. While HTTP requires deep learning and an advanced knowledge
          of JavaScript theory, HTTP/2 can make JavaScript load faster.
          
        4.Use a JavaScript content delivery network (CDN)
          ->A CDN is not a panacea. For example, if your project is not worldwide and you opt to use a CDN that doesn’t have a local 
          server in your country (e.g., the Russian Federation), this will increase page load time. Using a CDN is supposed to make
          things run faster, but in certain cases, it can have the opposite effect.
          
        5. Position CSS and JavaScript code in <head>
          ->This technique helps your page load faster, but requires pretty good knowledge of DOM and SCCOM. The idea is to bring a
          minimum amount of CSS and JavaScript code to the <head></head> section so it loads it immediately, while the more extensive 
          code is stored in separate .css and .js files, like usual.
