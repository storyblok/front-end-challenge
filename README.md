# Storyblok Front-end Challenge

Your task is to build a front-end for the FavTools application. It's a simple app to manage your favorite tools with their respective names, links, descriptions and tags.

The front-end must be built using Vue.js 3, using [the Storyblok Design System](https://github.com/storyblok/storyblok-design-system) and following the wireframes shown below.

## What will be evaluated

We want to assess your ability to develop and document a front-end application with a ready-made back-end. Will be evaluated:

- Well written and clean code;
- What tools were used, how and why;
- Your knowledge in JavaScript, HTML, CSS and tests;
- Your ability to commit;
- Your ability to document your part of the application.

## What we expect

- The screens following the wireframes below, using Storyblok Design System and the API available at the end of this document;
- [README.md](http://readme.md) containing basic information about the project and how to run it.
- Componentization and extensibility of Javascript components;
- Development of unit tests in Javascript.
- CSS naming clarity;
- Semantically structured HTML;
- Don't use NuxtJS.

## Bonus

- Concern about usability;
- Responsive interface.


# User Stories and wireframes

## 1: The user must be able to see the list of all registered tools

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75d16a8e-e4da-43e6-ab85-effcf60ee83e/Home.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/75d16a8e-e4da-43e6-ab85-effcf60ee83e/Home.png)

## 2: User must be able to add a new tool

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/73d42f2c-51b5-4b7e-8158-372335c712ae/add-tool.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/73d42f2c-51b5-4b7e-8158-372335c712ae/add-tool.png)

## 3: User must be able to remove a tool

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3c2a9c92-4ea4-4711-bf15-d897b2909421/remove-tool.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3c2a9c92-4ea4-4711-bf15-d897b2909421/remove-tool.png)

## 4: The user must be able to fetch tools dynamically (globally or using only tags)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e6287ba-3584-47c6-afba-831258a2b0f1/search.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e6287ba-3584-47c6-afba-831258a2b0f1/search.png)


# FavTools API
This repository contains a simple API for the Storyblok front-end challenge.
Requirements:
* NodeJS v5.2.0+

## How to run
Clone/download this repository, run `npm install` and `npx json-server db.json`. The API is located at `http://localhost:3000`.

## Routes
All POST requests to this API must contain the `Content-Type: application/json` header.
This API contains the following routes:

* `GET /tools` : list the tools
* `POST /tools` : create a new tool
* `DELETE /tools/:id` : delete tool with ID :id

To filter the tools in `GET /tools`, you can:
* do a global search using the query string `?q=:search`;
* perform a search for individual tags using the query string `?tags_like=:search`.

## Examples

### GET /tools

Request: 
```javascript
GET /tools
```
Response:
```javascript
[
    {
        id: 1,
        title: "Notion",
        link: "https://notion.so",
        description: "All in one tool to organize teams and ideas. Write, plan, collaborate, and get organized. ",
        tags: [
            "organization",
            "planning",
            "collaboration",
            "writing",
            "calendar"
        ]
    },
    {
        id: 2,
        title: "json-server",
        link: "https://github.com/typicode/json-server",
        description: "Fake REST API based on a json schema. Useful for mocking and creating APIs for front-end devs to consume in coding challenges.",
        tags: [
            "api",
            "json",
            "schema",
            "node",
            "github",
            "rest"
        ]
    },
    {
        id: 3,
        title: "fastify",
        link: "https://www.fastify.io/",
        description: "Extremely fast and simple, low-overhead web framework for NodeJS. Supports HTTP2.",
        tags: [
            "web",
            "framework",
            "node",
            "http2",
            "https",
            "localhost"
        ]
    }
]
```

### GET /tools?q=:busca

Request: 
```javascript
GET /tools?q=notion
```
Response:
```javascript
[
    {
        id: 1,
        title: "Notion",
        link: "https://notion.so",
        description: "All in one tool to organize teams and ideas. Write, plan, collaborate, and get organized. ",
        tags: [
            "organization",
            "planning",
            "collaboration",
            "writing",
            "calendar"
        ]
    }
]
```

### GET /tools?tags_like=:busca

Request: 
```javascript
GET /tools?tags_like=node
```
Response:
```javascript
[
    {
        id: 2,
        title: "json-server",
        link: "https://github.com/typicode/json-server",
        description: "Fake REST API based on a json schema. Useful for mocking and creating APIs for front-end devs to consume in coding challenges.",
        tags: [
            "api",
            "json",
            "schema",
            "node",
            "github",
            "rest"
        ]
    },
    {
        id: 3,
        title: "fastify",
        link: "https://www.fastify.io/",
        description: "Extremely fast and simple, low-overhead web framework for NodeJS. Supports HTTP2.",
        tags: [
            "web",
            "framework",
            "node",
            "http2",
            "https",
            "localhost"
        ]
    }
]
```

### POST /tools

Request:
```javascript
// POST /tools
// Content-Type: application/json
{
    "title": "hotel",
    "link": "https://github.com/typicode/hotel",
    "description": "Local app manager. Start apps within your browser, developer tool with local .localhost domain and https out of the box.",
    "tags":["node", "organizing", "webapps", "domain", "developer", "https", "proxy"]
}
```

Response:
```javascript
{
    "title": "hotel",
    "link": "https://github.com/typicode/hotel",
    "description": "Local app manager. Start apps within your browser, developer tool with local .localhost domain and https out of the box.",
    "tags":["node", "organizing", "webapps", "domain", "developer", "https", "proxy"],
    "id":5
}
```

### DELETE /tools/:id
Request:
```javascript
DELETE /tools/5
```

Response:
```javascript
// Status: 200 OK
{}
```


## Questions
Please, if you have any questions, send an e-mail to Gustavo: gmp@storyblok.com
 