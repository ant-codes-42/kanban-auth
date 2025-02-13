# Kanban Auth

## Description

This web application provides a full stack Kanban board with authentication. It utilizes PERN with JWT authentication.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contribute](#contribute)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

## Installation

NOTE: You must have [Node.js](https://nodejs.org) and [PostgreSQL](https://www.postgresql.org/) installed.

1. Clone this repo utilizing the green `<> Code` button to the folder of your choice. Optionally, download the source.

2. Create a .env file in the root of the server folder. Use the following structure:
DB_NAME='kanban_db'
DB_USER='postgres' (or your postgres username if different from default)
DB_PASSWORD='' (your postgres password)
JWT_SECRET_KEY='a random string' (literally a random string of your choosing)

3. In terminal, navigate to server/db. Log in to PostgreSQL shell and run '\i schema.sql' to initialize the DB.

4. Run 'npm i' to initialize and download dependencies. You will need Node.js which can be acquired from the [Node.js website.](https://nodejs.org)

5. Run 'npm run build' followed by 'npm run seed' from the root directory to initialize the app.

6. Run 'npm run dev' to initialize the site locally. Deployment of the web app is outside the scope of these instructions (follow your platform of choice's documentation).

## Usage

[Live version of the website](https://kanban-auth.onrender.com)

Sample logins (username, password):
JollyGuru, password
SunnyScribe, password
RadiantComet, password

Click login, and enter credentials to access the Kanban board. You may then create new Tasks or edit / delete existing ones.

## Contribute

[Please check out the repo here!](https://github.com/ant-codes-42/kanban-auth)

## Questions

The author maintains a [GitHub account here](https://github.com/ant-codes-42).

## License

This work is licensed under the MIT License.

Copyright 2025 Anthony Schwab

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.
