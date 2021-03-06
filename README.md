<div align="center"><img src="palette.png" width="150" height="150" /></div>
<h3 align="center">The Node.js performance palette</h3>
<br />

<h2>todo: Show benchmark data, otherwise people using this list are following as blindly as people who don't use this list</h2>

Performance is far from everything in a business, but what exactly is productivity worth if what you produce is absolute garbage? There is a balance between performance and productivity and you can easily tip the scale either way if not being cautious. One of the biggest mistakes is *blindly following others* without any kind of scepticism, such as blindly using the project with the most GitHub stars.

This list employs critical thinking by putting the most overhyped Node.js modules under the microscope and assigning them a score based on benchmarking results. Grades are meant to be rough pointers and should always be validated with your own benchmarks.

Meaning | Symbol
--- | ---
Very good | :ok_hand:
Good | :thumbsup:
Not good | :neutral_face:
Very bad | :thumbsdown:
Absolutely horrible | :shit:
Most used | :octocat:
Delusive | :trollface:
Biased | :heavy_dollar_sign:

## HTTP routers and helpers

Project | Grade | Extra
--- | --- | ---
[Sails.js](https://github.com/balderdashy/sails) | :shit:
[Hapi.js](https://github.com/hapijs/hapi) | :shit:
[Express.js](https://github.com/expressjs/express) | :thumbsdown: | :octocat:
[Koa.js](https://github.com/koajs/koa) | :thumbsdown:
[Fastify](https://github.com/fastify/fastify) | :thumbsup: | Focuses on faster JSON serialization
[Polka](https://github.com/lukeed/polka) | :ok_hand: | Aims to be a drop-in replacement of Express.js

## "Real-time" pub/sub, wrappers and helpers

Project | Grade | Extra
--- | --- | ---
[Socket.IO](https://github.com/socketio/socket.io) | :shit: | :octocat: :trollface:
[Engine.IO](https://github.com/socketio/engine.io) | :shit:
[Feathers.js](https://github.com/feathersjs/feathers) | :shit:
[SocketCluster](https://github.com/SocketCluster/socketcluster) | :thumbsdown:
[Primus](https://github.com/primus/primus) | :neutral_face:

## WebSocket implementations
Project | Grade | Extra
--- | --- | ---
[faye-websocket-node](https://github.com/faye/faye-websocket-node) | :thumbsdown:
[websockets/ws](https://github.com/websockets/ws) | :neutral_face: | :octocat:
[turbo-ws](https://github.com/hugmanrique/turbo-ws) | :shit: | :trollface:
[websocket-node](https://github.com/theturtle32/WebSocket-Node) | :thumbsdown:
[uws](https://github.com/uNetworking/uWebSockets-bindings) | :ok_hand: | :heavy_dollar_sign:

## Parsers, validators & formatters
Project | Grade | Extra
--- | --- | ---
[csv-parser](https://github.com/mafintosh/csv-parser) | :thumbsup:
[node-csv](https://github.com/adaltas/node-csv) | :shit: | :octocat:
[micnic/uv](https://github.com/micnic/uv) | :shit: | :trollface:

## Database connectors

todo

* Mongoose?
* MongoDB?
* Redis?
