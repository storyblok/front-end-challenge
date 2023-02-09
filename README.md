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

![home](https://lh3.googleusercontent.com/m5wnxAsE1q5Rl1YDlo3Cq4QXNlk3sZ3bFg-idwwyPa0CfxT5tEmLcpI67K6fsOlksFOXNv8juIkY2HNM4tAnvTmYzfixpT57_3z30cVWTpvrjwR06iBL9m2Tz7OtQko9boWfstoLFQ3MofgRBbpTzs8MaYoCwSlUGrjcgOLce_tbz2-7qkkNHh29rdxg3hUAf0zuGzJCwfnRggx6L4A_b7zKCoE_Bg0cSjw0E0ObxpdQS1yqZotDg2ftPI8H5GB4Xne_LENWtc0ttY7xQ3Uz7oSSVU5_N276h5O1mVV8FH1Span2pneIr9PQpO9wY2-u1xGFyH0wRfJGTXLJLVadyo7-zxtfcLi67-zxz7Sb47ehrDQXhMYxKbekBuRG6xpw4l4el8qIIEY6ezdE7KH4_3eustltLKbvpdvFMwhH4KTbIuOgRRspJk4MaZdYWCzMyqhUtPUUumWQIVW3A8Z7NDIBUk4lfZAOwoOcNoHrNWHvagUWq3QOAsIFfqH9anoEhTqj_P0pOrrqOYC4W9l7HUGkkyqr3br5WvP6m0LipRgMz86D5O4SzlB-3vuUt4prZ2dU_WQG8haJ6U-yFAE85AtDb5QhcdIaPYf5Ggvr5HVT9F3lQzxjaeQxGJfMm0H_I8G2B-KG2OQkvo7FnaEyWkZgbU_S2Iqy_h-PNwA9gaCgkPw0iBexTgimCFD_xpYRJ2zPi1EO1-YjIHOwQdvddMWhNtoHkG2mgdj1XIy_dXuy4HoE6tY-PxMl2sd-MZb1VvwtauOJl-r2j-Gx8xwYmRKqaFDu7-cJ16SS8EKThisgPjN5L_U-Y2rzd7PWbmxvkCNgIIouBxOwXeWBE12QJ1LvL3VvYAifD-5ZvmOkL_3c3UX4VqZ5hsFsgp_fE8Sx6oKlvLk7RvYBP7rfl7ZgHZIhA2gpcmq5VKXbdKVQ9GfD8e_LTkTjfEDnNIF4p_4DdNso0el4wz9COjq2lg=w2000-h1125-no?authuser=1)

## 2: User must be able to add a new tool

![add-tool](https://lh3.googleusercontent.com/rK6BYc4nYqoVicWMmlZfjRei0BLLxNtcaq1MDPzjbCpnBS4L7hs8K2qXoY24qnFirRBNTAMHcVTKyjaw-LPVNYZLS4PwKbFrvfpCkd1GsQLEVBH6AQ83-i0DcZdueU42wm3wJfgD76MCCzZI79dWhkM9JoMo-p8eiFHQbmPultu5ujcWLQiKFtf35_0wEOl2JxGWZytsGZOzFfg9p9F8lleXlCH74OSsjQ2yrEquROAt7vDRamfiL9iLt3kKm4dIO9qPAbSD4ZS8e1NM4UcqUL_zvqgzVC2i_f0QyOKpdlmL2b2KXoK1Q3vzgPNzNeDfJEuKubezwksbaGdvL0l-HQUjphgNpfWW7SSTB6bOtPiFXk30L1iUEfCFiMNGp01Gv1_GGj0h_gotqHYF7LRYw850gH03_cY4pA89vx0Vxf2xTVAfXFyAnES0aFDDR3_-tIiFMjkJ32QVCm_eUXQyrT-_kSUpxk_KRAV-lp8oqCiKskyYFAa09OIr0A67zl2PwLtrSiX9ZgI3jnVx-PA82RSzVd0rhy_XkgL3uWW_RV8xBLbFo30nIUgGReVHVyMFdlvix8Si27o_wbhpEDNdFybwqxSJrvpGS05D4vRinuuVWKDlGRupSaTDZFMiwz58JUvttRjaUW-fUoLcTKORKabl82e3JVPq-CAanQE0RM7Evg3jTvwKKAHd4lxOY7I_0zETh3FNaBNwQYLJMJOetGi0UNuRckKOEDZ18dN5LoRMMlY4dipLuXloDh5FRKbxPWdXG95Tr5KtoPJdbICao_25iIQFWwrI_vU-fdBl3joB4Xq22CCOVm4J2z5ZT0sNVN683-cpIWLsyEZx_iapeCA36ZFFwcrVD6DXoTexHvYpEMesE0Asyj3uRNO6S8WmGiHquWJTpF-rMdG6qnmQiZButmjGLAMom_i71YJ-l9w9KxxwLzlAE7hdPXNzOc0kDNnfPVgxLH9Mf3eUXQ=w2000-h1125-no?authuser=1)

## 3: User must be able to remove a tool

![remove-tool](https://lh3.googleusercontent.com/ClZyiUqlHNv1auCYji5kEsT4MOXMqT_Z5CS71lCvjB_VpRAIkP_Gi_LlY-7_rlekKJ-x4JPEz9hXoO6bpogV6cVz_MTqoCAN1VRlUkc8IMRg2XMyK0TfCk3mb8G0TcBd_3Emw2qA5uM2IlZn4V5AQyLyijpFXg0LhF-0Ip0IyoXrhc5K5FFTewUIajPUjNyuANFgM76oISX0nJWmdut9cu403tS4bNFWbMbnZ_J-FaKiDbbTddftJ8EF-KVUCTaq5XXYeGwDZtxkiduXWBdvlEFm_x0R6Pees3bxGVBvrhiu57KZdE5hRcSLXinc0VShKI_r8ESbnVxJOaC4fNhSbzB1pTu38sIjx59nttgYD8n9ed0a5f2w6ZHsRnwDJ9s44py2HetStMrPuHk0GP8lPRVtImY9keh1Z5aBja2FMClHQl6pQT-d14aSR85g1ZFF8EuAu1vMBbW83xu-kqgLqAzSrCmXnrnKbyeZavhyhqh9ue5e5GSkfNUI9soft4LBq1bxi03RdkGbIf3AEVelTHVQ14x6MNYeooFnZCouNw-HML1JQcBxOqnQ4zkzapA8CS5ohDrRSVOj-VtC-BWwHhW_nDxEPmjMLn1UVmAEqzaBLBIIIUxFgCkS7jgYTqEjhJgyzdnWSd3DM0T4RpDrX8XxtXC5zg1fPSH_vD8SOMkFCnrxeMlTdqXmGDvjHIEqMMe3OG0Wjlr2P0Lr6dOUOHcx6u6klKfG1HX1SGnZsbqc-T5jhvApCl1-bX_HewXeOgXAYL1dfgcw0zVrZHpPs4xdtSWe2871rq9dlxhqMo3Y4pDFxnpjYT-B-5m8XMbRrbG6WsFGoGeN9NCpeNRefT2izEqQmwIagtnciw1BZrbcKTeETkdvEXGMdeYO3sHFmd04l5TxaQpd1rXQ05JUpn_BCLHNxh73Vn1JxG27ThwHHO5UFQf3Na0zsQ6ahqX8Qrm9vJGynYKQvfzdDw=w2000-h1125-no?authuser=1)

## 4: The user must be able to fetch tools dynamically (globally or using only tags)

![search](https://lh3.googleusercontent.com/h6BE6yDSgxmCy8knXKzZxL5TDIR8sWSHSpSNwOKWu29n_S1HtqySBN_NOxp4nSZJMhwNaCKhpGlZXrkO-oCLwGVPazw_Ni5qq0tRYsw09Y_0RcZn5fA-WRfYm3LmtmwIPNqq8YzDUNJ2tcKUJDaus63Imgndp1p7NVnaB4fgtuGCSdMxcX2TuvLd922pGHWVt72si7nJ7L9f_92myqZUUmhQO-WcjGgTYMrCCZJlDWzx5oHKSZ6_gsEPuN32UAgyRXiV85fow71tduldPZaNCopfWjCkKY8_LTsqYt6gojgEc7pU-voRoIlFrtCAVwql8khkzDRJ8J9Fpp9NTMTclmWnQBjIhzkdtoF_bZ2hbVwHTx4fCmUh2Wpmy6f4k1NLDLYsv-4rPe5hxSSsnCFdx93l47WjdSN75PhoRYFClwuba3vUpMwfPLzll_v5MSgu0dq5WG2K1QJ0dsXvOZhOuohnCmRFe4Gczm--qZhzuKlxYsMAEVwUk-AyYaXonXkn4_p1f_2aEJdYXsHm38OSO5klt9Fsv4eg8xN0OK52KCnbXcLYesfMpdflzPyqQEV4yXQNyMYF9CC59cQwRV5zJq7F5CcUw_ozW2yLNu-IswjGbFO8YXI_uVehapk6PJUIRa5I6qQTWZSP2zMjhp8722Wuj53AlcoFx3fnr7g81Kmf_hV3fa0Fszlepfl86jU2TM-rJ6ZGMFIPSY84oE84ycDZJ2hwd7UNVbYHMj35Ani4Dbu8ewGIOwVnjDEag9g58imutW73X0Uq9QTxxC3GqUruEim-VzBkMTPIio9a6_3obfHPxz18PyyjsLi671Z7dlcpbaYuUNuVZgA0ZTJDUx3AKWjc2b0IXcLqctNu3j5Dxb_zKh082KKDt7QaF5m12V5gMGWNHmcGsdmrxLcO5VmQSlNUYh_dw_sdk1T_zjyHgL0S_hhJHEiCroYlgl1PNCmub0-yKl4419Usrw=w2000-h1125-no?authuser=1)


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
 