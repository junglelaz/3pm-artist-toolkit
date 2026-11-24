# 3PM Artist Toolkit

A standalone browser tool for independent musicians to preview an artist press kit and exchange release metadata as JSON.

## Project focus

A small product-design and creative-technology experiment: make an artist's story, releases and links portable in a simple format. The public toolkit demonstrates editable content, live preview and JSON import/export in a standalone browser experience.

**Related hosted product:** [3PM Presskit Creator](https://3pm.to/presskit-creator/). The hosted product and this standalone toolkit have different scopes; the repository is not the full 3PM platform.

## Run the demo

Download or clone this repository and open `index.html` in a modern browser. There is no install, account, build step or server. The example artist is fictional. Edit the JSON and update the preview, import an existing JSON file, or export the current kit.

## Press-kit format

The root object uses `version: 1`, an `artist` name, a `bio`, a `releases` array of objects with `title` and `year` strings, and a `links` array of objects with `label` and absolute HTTP or HTTPS `url` strings. Either array may be empty. Keep a copy of the original file if it contains fields outside this format. Export normalizes the supported fields and omits unknown ones.

## Scope

This repo contains the standalone toolkit. Its license applies to the toolkit code. It grants no rights to 3PM's name, platform, catalogue, or artists' recordings and artwork. See [3PM](https://3pm.to/) for the hosted music platform.
