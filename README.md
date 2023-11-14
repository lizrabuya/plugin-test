A Buildkite plugin for something awesome
 
## Usage

```yaml
steps:
  - label: "🔨 Running plugin"
    command: "echo plugin-test" 
    plugins:
      - lizrabuya
```

## And with other options as well

If you want to change the plugin behaviour:

```yaml
steps:
  - label: "🔨 Running plugin"
    command: "echo plugin-test" 
    plugins:
      - lizrabuya
          propagate-env-vars: false
```
## Configuration

### `propagate-env-vars` (optional)

Option to propagate env vars.

## ⚒ Developing

You can use the [bk cli](https://github.com/buildkite/cli) to run the [pipeline](.buildkite/pipeline.yml) locally:

```bash
bk local run
```

## 👩‍💻 Contributing

Your policy on how to contribute to the plugin!

## 📜 License

The package is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
