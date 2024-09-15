# JSON Server Example

## Source & Instructions

- Fake REST API: https://github.com/typicode/json-server/tree/v0
- Fake authentication & authorization flow: https://www.npmjs.com/package/json-server-auth 

## Installation

To get started with JSON server, follow these steps:

1. Clone this repository to your local machine

2. Install JSON server via npm:

```bash
npm install json-server
```
    
3. Start the JSON Server with the following command:

```bash
npx json-server db.json
```

## Get a REST API: endpoints

All products/comments:
- http://localhost:3000/products
- http://localhost:3000/comments

Specific product/comment:
- http://localhost:3000/products/1
- http://localhost:3000/comments/1