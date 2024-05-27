# Rate Limiting

In a node.js app, rate limiting algos can be utilised either on the:

-> app.js level by using app.use('/', tokenBucket). This will be the use-case to rate-limit all the endpoints.

-> router level as a middleware function. This will gave endpoint specific rate limiting.

<h4>I've tried to implement the middleware functions for all the following rate-limiting algorithms.</h4>

-> Token Bucket
-> Leaky Bucket
