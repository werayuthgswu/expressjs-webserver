# expressjs-webserver
Expressjs Application
1. At command prompt, create a folder expressjs-webserver <br>
	$ mkdir expressjs-[your id]
2. Change folder to the newly created folder <br>
        $ cd expressjs-[your id]
3. Initialize nodejs (this command will create package.json) <br>
        $ npm init -y
4. Open folder using vscode <br>
        $ code .
5. Install dependencies (libraries) <br>
        $ npm install -dev body-parser ejs express
5. In package.json, you should see dependencies (libraries) section with the libraries we install <br>  
6. In package.json, Add new line in the scripts section to look like below
   <pre>
     "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "start" : "node app.js"
     },
   </pre><br>
7. Copy contents from the project on github to yours. **Don't** overwrite existing files
8. Run nodejs application from the command prompt <br>
        $ npm start  (or you can run $ node app.js)
9. Open browser http://localhost:3000 
10. Try interact with the web page
11. Use ctrl+c to stop node application 
