# Udacity - Hosting Udagram Fullstack Application

**Version 1.0.0**

This project aims to give you a real-world scenario in which you would Use The AWS Cloud and CircleCi To Host and Deploy a Fullstack Application included the Database Also .This project barely touches the surface of what is possible but will prove your ability to use what you’ve learned in real-world scenarios.

---

## Table of Contents

- [Project Title](#Udacity-|-Image-Processing-API)

- [Instructions](#instructions)

- [Table of contents](#table-of-contents)

- [Usage](#Usage)

- [Dependencies](#Dependencies)

- [Installation](#Installation)

- [Testing](#Testing)

- [Built With](#Built-With)

- [Contribute](#contribute)

- [License](#License-&-Copyright)

---
## Instructions

[(Back to top)](#table-of-contents)

- The documentation folder attached in the project folder includes separate pages on different topics:
    1 - Infrastructure description.
    2 - App dependencies.
    3 - Pipeline process.
    
- This project require some prequesites and dependenscies to be installed.

---

## Usage

[(Back to top)](#table-of-contents)

You can Install this project to your PC using clone the repo to your github account then Download It as a ZIP File to your PC.

or Clone it using GIT `git clone` if you access it from GITHUB.

---

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```
---
### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres. <Place holder for link to classroom article>
1. In AWS, provision a s3 bucket for hosting the uploaded files. <Place holder for tlink to classroom article>
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd starter/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd starter/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.
  
  ####Ports:
             - Server port 3000.
             - Database port 5432.
---
## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.
---
## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
---
# Contribute

[(Back to top)](#table-of-contents)

**- Udacity**

**- EgFwd**

---

# License & Copyright

[(Back to top)](#table-of-contents)

**© Udacity And Mohammed Nasif.**
