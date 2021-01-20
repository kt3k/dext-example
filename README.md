a minimal example for running dext app.

Install dext:

```sh
deno install --allow-read --allow-write --allow-env --allow-net --allow-run --unstable -f -n dext https://deno.land/x/dext@0.10.1/cli.ts
```

Clone this repo:

```sh
git clone https://github.com/kt3k/dext-example.git
cd dext-example
```

Run dev server:

```sh
dext dev
```

Build static assets:

```sh
dext build
```

Now you'll get the static site assets in `.dext/static/`.

# License

MIT
