## Authors notes
REST Api I have made to make a beginning of a posting site, this is only a template for what there is to come.

Haven't made any frontend, this is pure backend to have the REST calls working.

To test it out, postman is a good option, but if you have another tool of your preference, feel free!

So far, the working urls are "localhost:3000", "/posts" and filling in the Id from a post, sitting at "/:postId".

Adding a new post can be done by:
```
{
  "title": "insert your flavor text here",
  "description": "give it a nice description"
}
```
<br>

### How to run it
Run the server by typing "node app.js" in the terminal

When the server is running, open another terminal and type "node client.js" to check out the posts



### Installation guide:

To run this you need node.js

Command to start the server:
```
npm start
```

*These commands are only needed in case you can't run it*
```
npm install express nodemod
npm install mongoose
npm install body-parser
npm install cors
```
<br>

Sorry if it feels lacking, were alone and didn't have the needed time (I know it's a bad excuse!)
