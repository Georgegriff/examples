# Hello World

A basic api**mesh** project.

# Setup

Ensure you have the api**mesh** tools installed installed.

# Run

```sh
cd hello-world
apim start
```

# Test with Curl

```sh
$URL=http://localhost:3000/echo
$DATA='{"text": "hello world"}'
curl -i -H "Accept: application/json" -H "Content-Type: application/json" -X POST -d $DATA $URL
```

You should see the following response:

```json
{
  "text": "hello world"
}
```
