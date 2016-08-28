# React Rally Day 1 - 2016
## Notes
TODO:
- Get slide links
- Watch FE Masters
- Read drboolean functional book (gitscm book and clean code)
- move all devops to AWS
- Learn go
- Learn bash

### Animation talk
- Saccade **
- Context shifting **
- Revealing
- Novel loaders had higher wait time and lower abandon rate vs gneric ones
- Add animation into the experience, not after
- React Europe 2015 - CSS TRANSITION GROUP
- Tools for the job:

-- CSS
- Small sequences and simple interactions

-- GSAP (Over 3 interactions) - Greensock
- Cross browser consistency

-- React-Motion
- Great for single movements

- Web animations API
- Staggers **

-- Request animation frame
- Use instead of setInterval/setTimeout (More performant)

-- React-canvas
- Mostly uiux
- 60fps

-- React VR
- AFRAME-REACT **

- Frontend master course **
- Animation SVG

Link: slides.com/sdrasner/react-rally

### Relay Talk
- Framework for building data-driven apps with react and graphQL
- Relay 2 - Ground up rewrite
- JS garbage collection -- JS VM **

### Debugging the debugger
-

### Composable world **
- Dot Chaining **
- Category theory **
- Throw it into a box (array)
- Loop - map / filter / reduce
- @drboolean
- https://drboolean.gitbooks.io/mostly-adequate-guide/content/

## Serverless GraphQL
- Function as a service == serverless
- google big data / query
- AWS Lambda (Cool but pain to setup)
- SERVERLESS https://github.com/serverless/serverless
- `npm install -g serverless@beta`
- `serverless create -t aws-nodejs`
- `serverless deploy`
- `serverless remove`
- SERVERLESS 101
- Function, Event, Resource (s3, dynamo, iam, etc), service
- React europe -- watch conf videos
- Use cases
- Marketing site + form
- Background jobs

## Multiprocess thread
- Flux standard actions
- redux-saga
- redux-loop

## React performance***
- Use FPS tool in chrome dev tools
- Perf addons
- Sentry / full story == neat
- RecordPerfButton
- Trigger slow behavior
- JS Profile
- Reactaddonsperf
- PureRenderMixin
- http://benchling.engineering/ - React pef
- GET SLIDES
- implement window.performance