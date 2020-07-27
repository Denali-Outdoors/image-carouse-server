# Project Name

A business review aggregator web app. Users have the ability to reserve a table at restaurants, browse pictures of the business, and leave a review. This repo is for the image carousel at the top of the page. Users and scroll through and when clicking on a specific image, a modal appears with an enlarged version of the picture. 

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)

## Usage

- NPM install
- NPM run react-watch
- create a .env file inside the root folder
- inside the .env file 

```
DATABASE=carousel 
HOST=[ip/localhost]
USER=root
PASS=[...]
```

- NPM run seedDB
- NPM start

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- etc

## Development

### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack
npm install
```

