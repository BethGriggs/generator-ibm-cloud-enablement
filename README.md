# IBM Cloud Enablement Generator

[![Bluemix powered][img-bluemix-powered]][url-bluemix]
[![Travis][img-travis-master]][url-travis-master]
[![Coveralls][img-coveralls-master]][url-coveralls-master]
[![Version][img-version]][url-npm]
[![DownloadsMonthly][img-npm-downloads-monthly]][url-npm]
[![DownloadsTotal][img-npm-downloads-total]][url-npm]
[![License][img-license]][url-npm]

> Work-in-progress

[img-bluemix-powered]: https://img.shields.io/badge/bluemix-powered-blue.svg
[url-bluemix]: http://bluemix.net
[url-npm]: https://www.npmjs.com/package/generator-ibm-cloud-enablement
[img-license]: https://img.shields.io/npm/l/generator-ibm-cloud-enablement.svg
[img-version]: https://img.shields.io/npm/v/generator-ibm-cloud-enablement.svg
[img-npm-downloads-monthly]: https://img.shields.io/npm/dm/generator-ibm-cloud-enablement.svg
[img-npm-downloads-total]: https://img.shields.io/npm/dt/generator-ibm-cloud-enablement.svg

[img-travis-master]: https://travis-ci.org/ibm-developer/generator-ibm-cloud-enablement.svg?branch=master
[url-travis-master]: https://travis-ci.org/ibm-developer/generator-ibm-cloud-enablement/branches

[img-coveralls-master]: https://coveralls.io/repos/github/ibm-developer/generator-ibm-cloud-enablement/badge.svg
[url-coveralls-master]: https://coveralls.io/github/ibm-developer/generator-ibm-cloud-enablement

## Pre-requisites

Install [Yeoman](http://yeoman.io)

```bash
npm install -g yo
```

## Installation

``bash
npm install -g generator-ibm-cloud-enablement
``

## Usage

Following command line arguments are supported
* `--bluemix {stringified-json}` -  used by Scaffolder to supply project information from `pman`. This will be referred as `projectConfig` in this document. You can also supply a local file containing compatible JSON object by using `--bluemix file:path/to/file.json`
* `--storages {stringified-array}` - used to add storage deployment to helm charts
* `--isDeployableContainer` -  if true add `container` to `deploy-target` in `cli-config.yaml`

## Development

Clone this repository and link it via npm

```bash
git clone https://github.com/ibm-developer/generator-ibm-cloud-enablement
cd generator-ibm-cloud-enablement
npm link
```

In a separate directory invoke the generator via

```bash
yo ibm-cloud-enablement 
```

