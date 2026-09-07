# .github
Action templates, and profile md

Run super-linter locally:
```
docker run \
-e LOG_LEVEL=DEBUG \
-e RUN_LOCAL=true \
-e DEFAULT_BRANCH=main \
-v /workspaces/.github:/tmp/lint \
--rm \
ghcr.io/super-linter/super-linter:latest
```
