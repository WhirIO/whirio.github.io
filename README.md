<p align="center">
	<a href="http://whir.io"><img src="static/img/whir.png" alt="whir.io" /></a>
</p>

### Getting started:
```
$> npm install -g whir
$> whir u=whir [options]
```

### Options:
- `u || username`: Your channel username.
- `c || channel`: The channel to join.
- `m || max`: Max. users per channel (Only for new channels).
- `t || timeout`: Disconnect after [timeout] seconds.
- `f || file`: Your settings file.

You may also store your settings in a file and use them instead of the arguments.

```
{
  "username": "whir",
  "channel": "developers",
  "max": 25
}
```

👍🏼
