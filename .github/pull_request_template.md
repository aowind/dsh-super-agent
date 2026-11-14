## What changed

<!-- one or two sentences; link the issue if there is one -->

## Why

<!-- the behaviour it fixes or the capability it adds -->

## How it was verified

- [ ] `npm test` (all five suites)
- [ ] exercised on a live DSH profile
- [ ] state inspected through `GET /api/super-agent/state`

## Checklist

- [ ] No token, secret or absolute home path is committed.
- [ ] New behaviour has an offline assertion when possible.
- [ ] User-visible text goes through `locale/` and the console dictionaries.
- [ ] `README.md` / `docs/` updated if the config surface changed.
