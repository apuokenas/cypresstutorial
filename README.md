[![cypresstutorial](https://img.shields.io/endpoint?url=https://dashboard.cypress.io/badge/detailed/ppzmww&style=flat&logo=cypress)](https://dashboard.cypress.io/projects/ppzmww/runs)

1. Check <cypress.json> containg `projectId` (this helps Cypress uniquely identify your project. If altered or deleted, analytics and load balancing will not function properly) into source control.
2. Record test runs to the Dashboard by passing a Record Key (that sends the failing tests, screenshots, and videos to the Dashboard) to run tests faster with parallelization and load balancing, debug failed tests in CI with screenshots and videos, and identify flaky tests:
`npx cypress run --record --key 2016eadb-9fbc-4091-8ca7-089fdfed17a2`