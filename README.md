# clap-val-action

A GitHub Action to download and run [`clap-validator`](https://github.com/free-audio/clap-validator).

### Suggested Usage

```yml
- uses: jatinchowdhury18/clap-val-action
  with:
    plugin_path: ./path/to/plugin.clap # <-- Path to the plugin you want to validate (required)
    version: 0.3.2                     # <-- Version of clap-validator you want to use (optional, defaults to 0.3.2)
    args: --only-failed                # <-- Extra arguments to be passed to clap-validator (optional)
```
