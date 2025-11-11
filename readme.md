# Terminal commands — Running Maestro Studio

Assumptions: repository or package is available locally or remotely. Replace placeholders (<...>) and choose npm/yarn/pnpm as needed.



Install dependencies
```bash

```






Open in browser (replace port as configured)
```bash
# on browser
$ maestro studio
open http://localhost:9999 on your  browser

```

Mobile / device helpers (optional)
```bash
# list connected Android devices
adb devices
```

get report from test run
```bash

maestro test --format hmtl yourflow.yaml

```

Common status/logs
```bash
# follow logs (Docker)
docker compose logs -f

# view Node logs (if writing to file)
tail -f logs/server.log
```