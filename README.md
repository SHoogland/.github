# .github

Action templates, and profile md

Run super-linter locally:

```bash
docker run \
-e RUN_LOCAL=true \
-e DEFAULT_BRANCH=main \
-e VALIDATE_MARKDOWN_PRETTIER=true \
-e FIX_MARKDOWN_PRETTIER=true \
-v /workspaces/.github:/tmp/lint \
--rm \
ghcr.io/super-linter/super-linter:latest
```
