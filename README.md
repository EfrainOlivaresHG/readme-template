# Project Name

[ ![Codeship Status for HGData/emr-sentence-extractor](https://codeship.com/projects/08d480d0-598b-0133-cf13-4e8f80416610/status?branch=master)](https://codeship.com/projects/110081)

Very short, couple of sentences on purpose of this tool/repo.

## Introduction
A slightly more detailed, but still high level description of the repo
* Include any links to diagrams that may be helful

## Usage (Quick getting started type of instructions)
### EMR Jar Usage

### Development Usage
* Check out the repo
* (Any setup that may be needed, config files like .artifactory for example?)
* Dependencies
* This project is on Codeship <link>
* Before submitting a PR...
* ?

### Auto Deployment
This project supports auto deployment to staging. In this case "staging" means building a fat runnable jar and having it deployed to s3://hg-code/hadoop/snapshots/. In order to do an auto release you must do the following:
* update the README.md with any pertinent information
* update the CHANGELOG.md with release notes information for the version you are deploying to
* update the version in build.gradle
* git checkout -b release-#.#.#
* git commit -am "meaningful version information message"
* git push origin release-#.#.#

## Tests
To run the tests
* ./gradlew integrationTests
* ./gradlew tests

## Maintainers
This repo is mantained by ___________

