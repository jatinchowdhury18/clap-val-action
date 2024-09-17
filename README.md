# clap-val-action

A GitHub Action to download and run [`clap-validator`](https://github.com/free-audio/clap-validator).

### Suggested Usage

```yml
- uses: jatinchowdhury18/clap-val-action
  with:
    plugin_path: ./path/to/plugin.clap # <-- Path to the plugin (required)
    version: 0.3.2                     # <-- Version of clap-validator (optional, defaults to 0.3.2)
    args: --only-failed                # <-- Extra arguments (optional)
```

## License

MIT license. Enjoy!
