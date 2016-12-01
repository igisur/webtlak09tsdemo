# WEBtlak # 09 TypeScript demo project

[![Build Status](https://travis-ci.org/igisur/webtlak09tsdemo.svg?branch=master)](https://travis-ci.org/igisur/webtlak09tsdemo)

Use `Gulp` task manager to execute single tasks

* `buildSrc` - build Typescript source to Javascript
* `buildTests` -   building just unit tests 
* `buildAndRunTestsWithCoverage` - build unit tests with code coverage in cobertura and HTML format.
* `tslint` - run Typescript linter to keep unified source code style. 'Checkstyle' is used as TSLint's output format for easy integration in Jenkins using [Checkstyle plugin](https://wiki.jenkins-ci.org/display/JENKINS/Checkstyle+Plugin)
