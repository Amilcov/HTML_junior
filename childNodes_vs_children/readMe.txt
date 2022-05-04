childNodes vs children 
1. Same:  intorc o lista de Noduri
2. Difference:  childNode include white Spaces (\n) / comments

ex: 
  <html>
  <head>
    <title>DOM Manipulation Fun</title>
  </head>
  <body>
      <h1>Example Page</h1>
      <div>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
    </div>
  </body>
</html>

documment.body.childNodes  // =[text, h1, text, div].  Note: text este \n between : 1. <body> & <h1>.  si 2. <h1> & <div>
documment.body.children    // =[ h1, div]
