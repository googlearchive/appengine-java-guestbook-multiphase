## appengine-java-guestbook-multiphase

Goes through the process of creating an App Engine guestbook using Java and Maven in phases.

1. phase1 -- UI Only
2. final -- Adds data access using [Objectify](https://github.com/objectify/objectify)

Written by Google Cloud Developer Relations

Please ask questions on [Stackoverflow](http://stackoverflow.com/questions/tagged/google-app-engine)

## Project setup, installation, and configuration

How do I, as a developer, start working on the project?

1. cd final  (or phase1)
1. `mvn clean appengine:devserver`

<!---
1. What dependencies does it have (where are they expressed) and how do I install them?
1. Can I see the project working before I change anything?

How do I run the project's automated tests?

* Unit Tests

* Integration Tests
 -->

## Deploying

### How to deploy

1. Create a project in [Google Cloud Console](https://cloud.google.com/console)
1. edit ...**/webapp/WEB-INFappengine.web.xml** and change **your-app-id**
1. `mvn clean appengine:update`

<!--- 
## Troubleshooting & useful tools

### Examples of common tasks

e.g.
* How to make curl requests while authenticated via oauth.
* How to monitor background jobs.
* How to run the app through a proxy.
 -->

## Contributing changes

* See [CONTRIBUTING.md](CONTRIBUTING.md)


## Licensing

* See [LICENSE](LICENSE)

