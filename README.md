# instant(1)

Spawn a http server in the current directory that instantly reloads
all connected devices as soon as a HTML, CSS, or JavaScript file is modified.

![screenshot](http://fgnass.github.io/images/instant.gif)

### Installation

```
$ npm install -g instant-server
```

### Usage

```
$ instant <port>
```

If the port is omitted a free random port is used and
`http://localhost:<random-port>` is opened in the default browser.

### Features

* Supports all major browsers including mobile devices and IE6
* No browser plugin required
* Uses the [instant middleware](https://npmjs.org/package/instant) under the hood

## License

MIT
