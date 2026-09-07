# .github
Action templates, and profile md

docker run \
-e LOG_LEVEL=DEBUG \
-e RUN_LOCAL=true \
-e DEFAULT_BRANCH=main \
-v /workspaces/.github:/tmp/lint \
--rm \
ghcr.io/super-linter/super-linter:latest