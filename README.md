# SSL3.IO Serverless/Lambda functions
Documention for how to use lambda and routes with SSL3.IO

## Handler format

In the code editor, the format of the function you are writing is this one:

```js
async function(req, res) {
  res.end("Hello SSL3.IO");
}
```

You can see the result of this function by browsing <a target="_blank" href="https://ssl3.io/hello">Hello World</a>.

your function needs to use `res.end(string)` to send data.

## The `req` object

The `req` object contains the request information. 

## The `res` object

The `res` object contains the response methods and parameters (like response code, response headers etc).
