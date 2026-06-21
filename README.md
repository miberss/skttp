# skttp

A tiny HTTP client for Skript.

```
set {_res} to http_get("https://api.example.com/thing")
broadcast http_body({_res}) if http_ok({_res}) = true
```

## Install
With [pacskage](https://github.com/miberss/pacskage):
```
/package install https://github.com/miberss/skttp
```

## License
Public domain (Unlicense).
