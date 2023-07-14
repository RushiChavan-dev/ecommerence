# How to Create an Ecommerce Site with React

The code in this repository accompanies the tutorial on creating a basic ecommerce site with React. It demonstrates the use of React Context for state management and includes a basic method for handling authentication and cart management.

## Requirements

* [Node.js](http://nodejs.org/)

## Installation Steps

1. Clone the repository.
2. Run `npm install` to install the required dependencies.
3. Start the backend server by running the following command in the terminal:

   ```
   ./node_modules/.bin/json-server-auth ./backend/db.json --port 3001
   ```

   This command starts the backend server, which uses `db.json` as the database and runs on port 3001.

4. Start the Create React App dev server by running `npm start`.
5. Open your web browser and visit [http://localhost:3000/](http://localhost:3000/).
6. Use the following login credentials to log in: 
   - Email: `regular@example.com` or `admin@example.com`
   - Password: `password`

## License

The code and examples in this repository are licensed under the MIT license.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
