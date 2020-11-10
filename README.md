# Happy Web

Application developed during the Next Level Week #3 ([Rocketseat](https://rocketseat.com.br/) :rocket:). Happy is an application that allows orphanages to sign up adding their info, such as their address and visiting hours, and users to search the map for the orphanage's addresses. Developed using React.js and Typescript.

<p align="center" width="100%">
    <img src="https://github.com/biagavirete/happy_frontend/blob/master/web/src/images/landing.png"> 
</p>

<p align="center" width="100%">
    <img src="https://github.com/biagavirete/happy_frontend/blob/master/web/src/images/happy-web.gif"> 
</p>

## Getting started

**Installing**
>Cloning the repository

```bash
$ git clone https://github.com/biagavirete/happy_frontend.git
$ cd happy_frontend
$ cd web
```

**Running**
> Installing dependencies

```bash
$ yarn
```

> To run the project an authentication token for Mapbox API is necessary. Create an account and generate a token to be used in the project. Add a .env file and add the token as the key for REACT_APP_MAPBOX_TOKEN.
Example:

```bash
REACT_APP_MAPBOX_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

> Running API. The back-end project is [here](https://github.com/biagavirete/happy_backend). Follow the instructions of that repository's README.


> Running React

```bash
$  yarn start
```

## Built with

* Typescript
* React
* React Leaflet
* React Icons
* Mapbox
