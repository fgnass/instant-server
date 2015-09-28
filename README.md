# instant(1)

Spawn a http server in the current directory that instantly notifies
all connected devices as soon as a HTML, CSS, or JavaScript file is modified.

![screenshot](http://fgnass.github.io/images/instant.gif)

### Installation

```
$ npm install -g instant-server
```

### Usage

```
$ instant -p <port> [dir]
```

### Options

* `-p | --port`: The port to listen to. If omitted, as free random port will be used.
* `-q | --quiet`: Hide listening message. If no port is provided, the port will be displayed.
* `-o | --open`: Open the default browser.
* `--delay <ms>`: Time to wait before reloading a resource (default is 10).

### Features

* Supports all major browsers including ancient ones as Android 2 or IE6
* No browser plugin required
* No need to add extra script tags to your HTML pages
* Incremental CSS updates (no page reload)
* Uses the [instant middleware](https://npmjs.org/package/instant) under the hood

## License

MIT
