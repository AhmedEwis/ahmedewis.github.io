---
# This file intentionally stops GitHub's legacy Jekyll "pages-build-deployment" build.
# The real site is built by Hugo in .github/workflows/publish.yaml.
# Without it, the legacy build overwrites the Hugo site with the README.
# Safe to delete once Settings -> Pages -> Source is set to "GitHub Actions".
---
{% stop_legacy_jekyll_build %}
