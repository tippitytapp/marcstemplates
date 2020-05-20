# Boiler Plate of Things to Do

1) To create the `package.json` file, you must first run `npm init -y`
    - [ ] - `package.json` included here is a template
    - [ ] - make sure you do not forget to create the `"server": "nodemon index.js"` and the `"start":"node index.js"` scripts
2) Start with creating the `index.js` file.
    - [ ] - bring in your `server.js` file
    - [ ] - `require('dotenv').config();`
    - [ ] - turn on your server using `server.listen(port => {})`
3) Create your `.env` file for any environment variables that you need (PORT, NODE_ENV, CONNECTION_URL, etc...)
4) Create your `server.js` file
    - [ ] - `require('express')`
    - [ ] - `require('helmet')`
    - [ ] - `requrie('cors')`
    - [ ] - `server = express();`
    - [ ] - set up your `server.use` functions

## Common Endpoints

| Action               | URL               | Method | Response         |
| :------------------- | :---------------- | :----- | :--------------- |
| Can reach API        |       /           | GET    |  valid 200 res   |
