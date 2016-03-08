# Tweets on a Globe!

Real-time visualization of geotagged tweets about a given topic, using d3, socket.io, and the Twitter API.

![tweets on a globe](https://raw.githubusercontent.com/joelgrus/twitter-globe/master/globe.gif)


Run it yourself with your favorite search phrase. First install the dependencies:

```bash
$ npm install
```

then create a `credentials.js` that looks like

```js
module.exports = {
  consumer_key: "...",
  consumer_secret: "...",
  access_token_key: "...",
  access_token_secret: "..."
};
```

then start it running:

```bash
$ node twitter.js
```

and finally navigate your browser to `localhost:9194`.

