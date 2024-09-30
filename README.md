# clap-val-action

A GitHub Action to download and run [`clap-validator`](https://github.com/free-audio/clap-validator).

### Suggested Usage

```yml
- uses: jatinchowdhury18/clap-val-action@main
  with:
    plugin_path: ./path/to/plugin.clap # <-- Path to the plugin (required)
    version: 0.3.2                     # <-- Version of clap-validator (optional, defaults to 0.3.2)
    args: --only-failed                # <-- Extra arguments (optional)
```

If your plugin has spaces in its name, then the plugin path must include additional quotes:
```yml
- uses: jatinchowdhury18/clap-val-action@main
  with:
    plugin_path: "\"./path/to/my plugin.clap\""
```

It's also possible to validate multiple plugins:
```yml
- uses: jatinchowdhury18/clap-val-action@main
  with:
    plugin_path: ./path/to/plugin1.clap ./path/to/plugin2.clap
```

## License

MIT license. Enjoy!
