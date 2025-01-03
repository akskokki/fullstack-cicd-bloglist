This was an exercises for the CI/CD section of the FullStack Open course.

I took an existing application I had made earlier in the course, and

- restructured it to make it easier to work with in a single repository
- added a workflow for running unit and e2e tests on pushes and PRs
- deployed the application to fly.io
- added an automated deployment pipeline when pushing to main, given that the tests have passed
- protected the main branch from direct pushes, requiring an approved pull request for any additions

The application is running at https://fullstack-cicd-bloglist.fly.dev/. You can log in with the credentials testUser and testPass, however, be wary of some extraordinarily ugly test data.
