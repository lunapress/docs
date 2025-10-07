# LunaPress Docs

## Dev

1. Install [DDEV](https://ddev.com/get-started/)
2. Rename `.ddev/.env.example` to `.ddev/.env`
3. Launch the website

```shell
ddev start
```

4. Start development

```shell
ddev dev
```

### Commands in a container

The launch takes place in the `docs` folder:

```shell
ddev pnpm run COMMAND
```