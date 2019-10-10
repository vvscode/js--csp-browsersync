# Browsersync wrapper to bypass Content-Security-Policy restrictions

## How to use:

```bash
npx csp-browsersync http://ya.ru
```

You can control server port (default is 10000), and ui-port (default is 10001) with `BROWSER_SYNC_PORT` and `BROWSER_SYNC_UI_PORT` environment variables.


To expose website to external web you can add `--tunnel` as first param

```bash
npx csp-browsersync --tunnel http://ya.ru
```
