## How to run locally
This is built using the [GOV.UK Prototype Kit](https://govuk-prototype-kit.herokuapp.com/docs).

To run it locally, clone it down, run `npm install` and then `npm start`. It'll then tell you a port to go to in the browser.

#### Alternatively run it via docker & docker-compose
Depends on [docker install](https://docs.docker.com/install/) and [docker-compose install](https://docs.docker.com/compose/install/)
1. `docker-compose build`
2. `docker-compose up`

Or get a bash console where you can run `npm` cmds via the built container (ensure step 1 above is done)
`docker-compose run --rm --service-ports --entrypoint="bash" goose`

Run the tests via docker
`docker-compose run --rm --entrypoint="npm run test" goose`

## Suggesting changes
Feedback is welcome. Either [submit an issue](https://https://github.com/CodeYourFuture/CYF-Record-A-Goose-Project/issues), or [open a PR](https://github.com/CodeYourFuture/CYF-Record-A-Goose-Project/pulls).

## Resources for further learning
- [Udacity Accessibility course](https://www.udacity.com/course/web-accessibility--ud891) - good for futhering knowledge about writing accessible code
- [GDS WCAG 2.1 Primer](https://alphagov.github.io/wcag-primer/) - good for helping you understand the Web Content Accessibility Guidelines
- [GDS guidance how to conduct a basic accessibility audit](https://www.gov.uk/government/publications/doing-a-basic-accessibility-check-if-you-cant-do-a-detailed-one/doing-a-basic-accessibility-check-if-you-cant-do-a-detailed-one) - mentioned above but listed here as well
- [a11y weekly](https://a11yweekly.com/) - a good weekly newsletter about accessibility

Any other suggestions, free free to add them!

## Other versions of the exercise
This version is forked (and revived) from the MoJ archived repo. Other forks:

- [NHS Accessibility exercise](https://github.com/nhsuk/accessibility-training)
- [Coop accessibility exercise - 'Report a leaky bag of flour'](https://github.com/coopdigital/return-a-leaky-bag-of-flour)
