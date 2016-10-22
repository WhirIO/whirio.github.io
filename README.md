<p align="center">
	<a href="http://whir.io"><img src="static/img/whir.png" alt="whir.io" /></a>
</p>

### Getting started:
```
$> npm install -g whir.io
$> whir.io --user=stefan [options]
```


### Options:
- `--user`: Your channel username.
- `--channel`: The channel to join.
- `--max`: Max. users per channel (Only for new channels).
- `--timeout`: Disconnect after [timeout] seconds.
- `--file`: Your settings file. This will override other options.

If you want store your settings in a file instead of passing arguments.

```
{
  "user": "stefan",
  "channel": "development",
  "timeout": 10,
  "max": 25
}
```

### License

[MIT](https://github.com/WhirIO/Client/blob/master/LICENSE)

### Enjoy!
