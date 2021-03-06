[![Build Status](https://travis-ci.com/Labs-EU4/hackathon-portal-server.svg?branch=develop)](https://travis-ci.com/Labs-EU4/hackathon-portal-server) [![Coverage Status](https://coveralls.io/repos/github/Labs-EU4/hackathon-portal-server/badge.svg?branch=develop)](https://coveralls.io/github/Labs-EU4/hackathon-portal-server?branch=develop) [![Netlify Status](https://api.netlify.com/api/v1/badges/c76b92d4-4a5a-4340-b38e-d9411cfb4560/deploy-status)](https://app.netlify.com/sites/suspicious-kare-dc8a3a/deploys)

### Hackton

A comprehensive portal for hackathons where students can submit their work and judges can evaluate in one place. It is an app that helps you organize and evaluate Hackathons.

### Summary:

A comprehensive portal for hackathons where students can submit their work and judges can evaluate in one place

### Project Overview

[Trello Board](https://trello.com/b/SEMsn9ik/hackathon)

[Product Canvas](https://www.notion.so/50bba1019cc546a7af4b6bd54ed0979a?v=f4161624690443c2bc6c90d3033aded5)

[UX Design files](https://www.figma.com/file/4hAdkxUDAwWWJneMmbbNji/Mock-Ups?node-id=193%3A0)

### Table of Content

1. [Getting started](#getting-started 'Getting Started')

- [Install dependencies](#installation 'Installation')
- [Enviroment variables](#enviroment-variables 'Enviroment Variables')

2. [Running the tests](#running-the-tests ' Running the tests')

- [Break down into end to end tests](#break-down-into-end-to-end-tests 'Break down into end to end tests')

3. [Contributing](#Contributing 'Contributing')
4. [Issue/Bug Request](#Issues 'Issue/Bug Request')
5. [Feature Requests](#Feature-Requests 'Feature Requests')
6. [Pull Requests](#Pull-Requests 'Pull Requests')
7. [Pull Request Guidelines](#Pull-Request-Guidelines 'Pull Request Guidelines')
8. [Deployment](#Deployment 'Deployment')
9. [Tech stack](#Tech-stack 'Tech stack')
10. [Authors](#Authors 'Authors')
11. [API Documentation](#API-Documentation 'API Documentation')
12. [Acknowledgments](#acknowledgments 'Acknowledgments')
13. [Version](#Version 'Version')
14. [License](#License 'License')

### Getting Started

This repository contains only the frontend implementation of the Hackathon project. You can click **[here](https://github.com/Labs-EU4/hackathon-portal-server.git)** to check the backend implementation.

Start by cloning the repository to your local machine

```bash
git clone https://github.com/Labs-EU4/hackathon-portal-server.git

```

To install this application, you'll need Node.js 8+ (which comes with npm) installed on your computer.

Install dependencies:

Create a `.env` file on your root directory and populate it based on examples in `.env.example`.

Next install the package dependencies by running

```bash
npm install
```

After that start or build the application by running

```bash
npm start # For a local development
```

### Enviroment Variables

The following should be inside `.env` file for the app to function correctly.

```
 REACT_APP_API_URL=https://hackathon-review-deployment.herokuapp.com/
```

### Running the tests

```bash
npm test

```

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./CODE_OF_CONDUCT.md). Please follow it in all your interactions with the project.

### Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Deployment

This project has been deployed with [Heroku] at .

### Tech stack

This app was built with

- [Node.js](https://nodejs.org/en/)- is a Javascript Runtime Engine.
- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.
- [Knex](http://knexjs.org/) - is a "batteries included" SQL query builder for Postgres, MSSQL, MySQL, MariaDB, SQLite3, Oracle, and Amazon Redshift designed to be flexible, portable, and fun to use..
- [Postgresql](https://www.postgresql.org/) - PostgreSQL is a powerful, open source object-relational database system.

### Authors

|                                          [Anthony Campbell](https://anthonycampbell.dev)                                          |                                         [AbdelIdir ](https://github.com/AbdelIdir)                                          |                                               [Ekanem David](https://github.com/dueka)                                                |
| :-------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: |
|      [<img src="https://avatars3.githubusercontent.com/u/45029641?s=400&v=4" width = "200" />](https://anthonycampbell.dev)       |   [<img src="https://avatars0.githubusercontent.com/u/53605229?s=460&v=4" width = "200" />](https://github.com/AbdelIdir)   |          [<img src="https://avatars2.githubusercontent.com/u/38921132?s=460&v=4" width = "200" />](https://github.com/dueka)          |
|                                                            Team Leader                                                            |                                                             Dev                                                             |                                                                  Dev                                                                  |
|                   [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/AnthonyJCampbell)                   |                   [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/AbdelIdir)                    |                          [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/dueka)                           |
| [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/anthonyjcampbell/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/idir-abdel/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/ekanem-david-8711719a) |

<br>

|                                                                                          [Emma Andrews](https://github.com/ELAndrews)                                                                                          |                                        [John Afolabi](https://github.com/john-afolabi)                                        |                                             [Karim Bertacche](https://github.com/john-afolabi)                                             |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://media-exp1.licdn.com/dms/image/C5603AQFRpv9tGUnasQ/profile-displayphoto-shrink_200_200/0?e=1587600000&v=beta&t=mN_NQjxyyVHRDkl0n-OpMoXj1qkYcuYGB5rQIPTBx7c" width = "200" />](https://github.com/ELAndrews) |  [<img src="https://avatars3.githubusercontent.com/u/19263499?s=460&v=4" width = "200" />](https://github.com/john-afolabi)   |        [<img src="https://avatars3.githubusercontent.com/u/49835145?s=460&v=4" width = "200" />](https://github.com/KarimBertacche)        |
|                                                                                                              Dev                                                                                                               |                                                              Dev                                                              |                                                                    Dev                                                                     |
|                                                                     [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/ELAndrews)                                                                     |                   [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/john-afolabi)                   |                        [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/KarimBertacche)                         |
|                                            [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/emma-andrews-b26768169/)                                             | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/john-afolabi/) | [ <img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/karim-bertacche-64b270156/) |

### API Documentation

This documentation was generated by Postman and can be found https://documenter.getpostman.com/view/8702366/SWLfcTEZ

#### Acknowledgments

- [Alex Emedeme](https://github.com/AlexEntrepreneur) - Engineering Manager
- [Lambda](https://lambdaschool.com/)

### Version

This is version 0.0.1

### License

The MIT License (MIT)

Copyright (c) 2020 Hackathon

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
