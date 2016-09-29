# sp-rest-proxy - SharePoint REST API Proxy for Node.js and Express local serve

> Concept for REST API proxy to SharePoint tenant as if it were a local API.

[![NPM](https://nodei.co/npm/sp-rest-proxy.png?mini=true&downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/sp-rest-proxy/)

[![npm version](https://badge.fury.io/js/sp-rest-proxy.svg)](https://badge.fury.io/js/sp-rest-proxy)
[![Downloads](https://img.shields.io/npm/dm/sp-rest-proxy.svg)](https://www.npmjs.com/package/sp-rest-proxy)

Allows to perform API calls to local Express application with forwarding the queries to a remote SharePoint instance.

This concept was created to show how is could be easy to implements real world data communications for SharePoint Framework local serve mode during web parts debug without deployment to SharePoint tenant.

## Supported SharePoint versions:
- SharePoint Online
- SharePoint 2013
- SharePoint 2016

## How to use:

### Install:

1\. Clone the project:

```bash
git clone https://github.com/koltyakov/sp-rest-proxy
```

2\. CMD to the project folder.

3\. Install dependencies:

```bash
npm run build
```

4\. Run the server:

```bash
npm run serve
```

Prompt credentials for a SharePoint site.

5\. Navigate to http://localhost:8080

6\. Ajax REST calls as if you were in SharePoint site page context:

![REST Client Example](./docs/img/client-example.png)