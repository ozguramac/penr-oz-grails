## Download and Installation

To begin development on this site:
* Clone the repo: `git clone https://github.com/ozguramac/penr-oz-grails.git`
* [Fork, Clone, or Download on GitHub](https://github.com/ozguramac/penr-oz-grails)

### How do I get set up? ###

* Summary of set up: Recommend using Intellij IDEA to build/run.
* Configuration: groovy, Grails
    - Please follow the instructions to install the [asciidoctor-epub3](http://asciidoctor.org/docs/convert-asciidoc-to-epub/) ruby gem

* How to build: 
```
    gradle publishGuide

    groovy book.groovy
```
* How to run tests: TBD
* How to run:
```
    asciidoctor-epub3 -D build/bookOutput build/book/creating-your-first-grails-app.adoc
```
* Deployment instructions: TBD

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact

## Copyright and License

Copyright 2017 [Derin Works LLC](http://www.derinworksllc.com)

