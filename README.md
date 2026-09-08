# .github
Action templates, and profile md

Run super-linter locally:
```bash
docker run \
-e RUN_LOCAL=true \
-e DEFAULT_BRANCH=main \
-e FIX_YAML_PRETTIER=true \
-e FIX_JSON_PRETTIER=true \
-v /workspaces/.github:/tmp/lint \
--rm \
ghcr.io/super-linter/super-linter:latest
```
