## Getting started
* `npm i`

## Todo

create a basic server with express
that will send back the index.html file on a GET request to '/'
it should then send back jsonData on a GET to /data

## Fetch all branches locally

```
git branch -r | grep -v '\->' | while read remote; do git branch --track "${remote#origin/}" "$remote"; done
git fetch --all
git pull --all
```

+ Website site: http://fem-node-api.netlify.com/

+ Course: https://app.pluralsight.com/player?course=api-design-nodejs-express-mongo
+ start mongo `mongod`

```js
http POST localhost:3000/api/users username=andra
