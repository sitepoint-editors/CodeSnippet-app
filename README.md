# Code Snippet Application

This repo contains the source code for a code snippet application built with NextJs and powered by FaunaDB for the back-end. It utilizes Google authentication to allow users create snippets, edit and delete created snippets. 

## Requirements

* [Node.js](http://nodejs.org/)
* [FaunaDB](https://fauna.com/)

## Installation Steps

1. Clone repo
2. Run `npm install`
3. Set up a FaunaDB database with a collection "codesnippet".
4. Set up access credentials for FaunaDB and Google Cloud console in the `.env` file
5. Run `npm run dev`
6. Visit http://localhost:3000

## License

SitePoint's code archives and code examples are licensed under the MIT license.

Copyright © 2021 SitePoint

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
