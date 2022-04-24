<html>
<body>
  <h1 align="center">Learning Baisc Fundamental Of TypeScript</h1>
  
  <div>
    <h2>What is TypeScript?</h2>
    <ol>
      <li>A programming language which can use as an alternative to JavaScript.</li>
      <li>Is a superset of JavaScript whch means that it can expands the languge with additional features and syntax.</li>
      <li>Allow to use strict types which means that if variable declare data type as 'string' type, we can't just change the type later to a 'number' or 'boolean'.</li>
      <li>With strict types in place, error checking and debugging process becomes easier and code will be less error-prone. </li>
    </ol>
  </div>
  <div>
    <h2>How TypeScript Works?</h2>
    <ol>
      <li>As browser doesn't understand TypeScript in the same way they do JavaScript, so when writing TypeScript we have to compile it into JavaScript in order for the browser to understand.</li>
      <li>To use TypeScript, we need to install <a href="https://nodejs.org/en/">node js</a> in our computer to install TypeScript.</li>
      <li>After installing node js, open up terminal and type 'npm install -g typescript' and press enter to start installing typescript.</li>
      <li>Open your ide editor and create a folder and with index.html and app.ts files. We are writing typescript code on app.ts.</li>
      <li>Typescript file should end with .ts extension</li>
      <li>In html file include a script tag pointing to app.js. Why app.js is because browser only recognise javascript file. If we point to app.ts and console log browser wouldn''t understand and it will not log result to console.</li>
      <li>In order to let browser understand typescript we need to compile app.ts to app.js by typing 'tsc app.ts' in the terminal. Once the command line is entered, typescript will automatically convert app.ts to app.js by producing another app file with .js extension.<li>
      <li>Now we can write some code and console log on app.ts, compile it and go to index.html browser, open up developer console and you will see the log. </li>
      <li>To save the hassel of keep typing 'tsc app.ts' to compile the file, we can type 'tsc app.ts -w' to set auto compile. '-w' means watch mode</li>
    </ol>
  </div>
</body>
</html>
