# Express.js
- Web framework to handle the requests and responses of a server
- Below code starts a server
```js
app = express()
```
- listen is used to specify the port number where the server must listen and also provide a callback that is called when the server starts listening
- Various URLs specified using get function are listened by the server and the specified function is called

# For production
- Port number comes under the category of sensitive information (others include db_name, db_password, etc)
- Hence, must be stored as the environment variables in a separate file called .env
- The environment variables present in .env are accessed using dotenv in the other files
- The environment variables must also be specified while deploying our code into production