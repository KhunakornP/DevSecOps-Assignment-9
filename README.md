# DevSecOps-Assignment-9
Classwork for DevSecOps 2026-01219493 course from Kasetsart University

The sample application comes from Bootstrapping Microservice Second Edition

# The application
This example project demonstrates end to end testing a microservice with Cypress.

First you must boot the microservices application:

```bash
docker-compose up --build
```

Now install dependencies for testing:

```bash
cd example-4
npm install
```

Then run headless Cypress tests:

```bash
npm test
```

Or to show the Cypress UI:

```bash
npm run test:watch
```