# Sabesp Mananciais API
A simple scraping application to vizualize data about water in São Paulo.

[![Build Status](https://travis-ci.org/rafaell-lycan/sabesp-mananciais-api.svg?branch=master)](https://travis-ci.org/rafaell-lycan/sabesp-mananciais-api)
[![node](https://img.shields.io/node/v/gh-badges.svg)]()
[![GitHub release](https://img.shields.io/github/release/rafaell-lycan/sabesp-mananciais-api.svg)]()
[![License](http://img.shields.io/:license-mit-blue.svg)](https://github.com/rafaell-lycan/sabesp-mananciais-api/blob/master/LISENCE)


#### A little bit about the technology envolve in this project:
- Node.js 0.10.x
- Express 4.11.2
- Request 2.53.0
- Cheerio 0.18.0
- Promise 6.1.0


#### Dev Dependencies:
- Nodemon 1.3.6
- JSHint 2.6.0

#### Route Schema:
Description | Method | URL | Params
--- | --- | --- | ---
Get data of today | GET | `/` | NULL
Get data of a specific day | GET | `/:date` | YYYY-MM-DD

#### OBS:
Isn't possible get data before January 1th, 2003.