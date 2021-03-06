| Statements | Branches | Functions | Lines | Build Status |
| -----------|----------|-----------|-------| ------------ |
| ![Statements](https://img.shields.io/badge/Coverage-20%25-red.svg "Make me better!") | ![Branches](https://img.shields.io/badge/Coverage-0%25-red.svg "Make me better!") | ![Functions](https://img.shields.io/badge/Coverage-33.33%25-red.svg "Make me better!") | ![Lines](https://img.shields.io/badge/Coverage-20%25-red.svg "Make me better!") | ![BuildStatus](https://img.shields.io/badge/Build-Passing-brightgreen.svg "Building Status") |

# Store Revenue Map

- [Store Revenue Map](#store-revenue-map)
  - [Getting Started](#getting-started)
  - [Build Instructions](#build-instructions)
  - [Third-party Libraries](#third-party-libraries)
  - [TODO](#todo)

## Getting Started

1. Download or clone this repository.
```
https://gitlab.com/olavoparno/gfn_frontend_challenge_olavo-parno.git
```
2. Run ***npm install*** in order to install all dependencies.
3. Run ***npm start*** in order to serve it under the following address: http://localhost:8080/.

## Build Instructions

* After all dependencies have been installed, run ***npm run build*** and serve the files in the ***dist*** folder.

## Third-party Libraries

* [React-Leaflet](https://react-leaflet.js.org), map library derived from [Leaflet](https://leafletjs.com) itself.

## TODO

* Please note that this project needs a Redux/Mobx implementation in order to solve performance and maintenance issues. As a paliative, all components are run under the method ***shouldComponentUpdate***.
* This project also needs to have unit tests implemented specially because the pattern ***red, green, refactor*** was not followed.
