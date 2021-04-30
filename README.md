import useBaseUrl from "@docusaurus/useBaseUrl";

# Amazon Connect Salesforce CTI Adapter Setup and Installation Guide

<p align="center">
  <img src={useBaseUrl('/static/img/lightning/image1.png')} />
</p>

This website is built using [Docusaurus 2](https://v2.docusaurus.io/), a modern static website generator. This guide details the integration between Amazon Connect and Salesforce Lightning. It covers the installation, configuration, and operation of the two primary components of the integration: the Amazon Connect CTI Adapter for Salesforce and the AWS Serverless Application Repository for Amazon Connect Salesforce integration.

# Usage

## Installation

```console
npm install
```

## Local Development

```console
npm start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
npm build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

```console
GIT_USER=<Your GitHub username> USE_SSH=true npm deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

## Build pdf

```console
npm build-pdf
```

This command will build a pdf from the documentation and output the files in the `pdf/` folder.

## Initialize githooks

```console
npm init-githooks
```

This command will set up the githooks in the `.githooks/` folder.
