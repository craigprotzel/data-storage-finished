Data Storage Finished
---------------------

**Configured for Glitch**
1. In `index.js`, set the port variable to be equal to the environment variable
```
let port = process.env.PORT || 3000;
app.listen(port, () => {
    console.log('listening at ', port);
});
```
2. In `package.json`, set the node engine to v16
```
"engines": {
    "node": "16.x"
},
```
3. Made sure to include a `.gitignore` file with the necessary items
```
.DS_store
node_modules
```
