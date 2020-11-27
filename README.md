# pbrn-auth
[![Build Status](https://travis-ci.com/MUHC-DP-Project/pbrn-auth.svg?branch=main)](https://travis-ci.com/MUHC-DP-Project/pbrn-auth)
## Purpose 

pbrn-auth is a microservice serving as the main source for user authentication. This service serves as the key handshake necessary by a client before the muhc-gateway and microservices suite can be accessed.

**Note:** This API is ***internal only*** and should not be accessible by external clients.

## How to run
For information about the technology stack used in this repository please refer to [Tech Stack](https://github.com/MUHC-DP-Project/pbrn-gateway/wiki/Tech-Stack)
- Prerequisites: Have Node.js (v12.19.0) installed
- clone the repository
- `npm install`  to install all dependencies
- `npm start` to run the service
