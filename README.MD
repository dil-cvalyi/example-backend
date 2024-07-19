## Questions
### Backend
#### NodeJS
* What is the package.json
* What is the package-lock.json
* How routing works in a nodejs backend (e.g fastify or express)
  * What happens with a request when it hits an endpoint
* Why/how an API becomes RESTful
  * Have you heard about GraphQL? (If yes elaborate)
* What does authentication mean
  * JWT in general
  * Headers
  * Cookies
* What does authorization mean

#### Database
* How a database looks like
  * What are the building blocks
* What type of basic commands do you know
* What do you know about constraints, why are they important
* What are database indices, what they help us achieve


### Combined question
* Let's say we have a frontend and a backend. We are requesting some data on the FE from our BE.
  Can you describe the flow that is happening, or should happen from the moment the request leaves the browser.
  * If not mentioned ask about:
    * BE side validation
    * Status code
    * Authentication
    * Authorization
    * Error handling

Idea:
Put together a simple repo with backend and some SQL.
Have a PR opened with some issues. Let the candidate go through the PR and see what he/she "flags" and why.


### Infrastructure
#### Version control
* What is a version control system
* Why do we need them
* Name a couple of commands you use in git
  * Have you heard of `git bisect`?

#### Docker
* What are docker containers
* Why do we like docker containers ("build" it once, run it "everywhere")
* Running our backend in one container, running the database in another
  * How can you reach the database from the backend (e.g.: open ports and localhost, docker network and "aliases")

#### Monorepo
* Have you heard about monorepos
  * What tools have you used to maintain it (npm, pnpm, nx, yarn)
  * What are the advantage and disadvantage of it
    (e.g. adv: everything in one place. Disadv: can grow large really fast)

#### CI/CD
* What CI/CD stands for
* Have you seen/used/configured one before?
  * Why they are a game changer? (e.g: no manual involvement with the deployment, less possibility for errors)

#### IDE
#### Server Client architecture
