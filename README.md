# alfred-hotel

[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

> [Alfred 3+](https://www.alfredapp.com/) workflow that lets you start, stop and open [Hotel](https://github.com/typicode/hotel) apps

![alfred hotel workflow screenshot in action](screenshot.png)


## Requirements

- [Node.js](https://nodejs.org) >= 6.4
- [Hotel](https://github.com/typicode/hotel) >= 0.8
- [Alfred with Powerpack](https://www.alfredapp.com/powerpack/) >= 3


## Install

```shell
$ npm install -g alfred-hotel
```


## Usage

In Alfred, type `hotel` to list all [Hotel](https://github.com/typicode/hotel) apps, press <kbd>Space</kbd> to search through list.

With selected app you can:

- <kbd>Enter</kbd> to start and open app in default browser (http://example.dev)
- <kbd>Alt</kbd> + <kbd>Enter</kbd> to open app without local domain (http://127.0.0.1:50409)
- <kbd>Command</kbd> + <kbd>Enter</kbd> to start/stop selected app
- <kbd>Fn</kbd> + <kbd>Enter</kbd> to restart selected app
- <kbd>Command</kbd> + <kbd>C</kbd> to copy app url
- <kbd>Ctrl</kbd> + <kbd>Enter</kbd> to open app folder
- <kbd>Shift</kbd> to preview url with quicklook


## Settings

By default workflow works with following Hotel settings:

- Hotel is available at `http://localhost:2000`
- Local domains are in `.localhost` zone

You can change this in [`~/.hotel/conf.json`](https://github.com/typicode/hotel#configurations-logs-and-self-signed-ssl-certificate).


## Related

- [alfy](https://github.com/sindresorhus/alfy) - Create Alfred workflows with ease
- [hotel](https://github.com/typicode/hotel) - A simple process manager for developers


## License

MIT © [John Grishin](http://johngrish.in)
