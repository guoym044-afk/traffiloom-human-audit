# TraffiLoom Human Audit

This directory is the standalone static deployment package for the P1 human
audit. Open `index.html` in a modern browser or publish this directory through
any static-site host.

## Annotation workflow

1. Enter a unique annotator ID.
2. Review every case using only the public instruction, candidates, rule cards,
   and system output shown on the page.
3. Complete all seven required judgments.
4. Use **Export JSON** when all 60 cases are complete.
5. Return the exported JSON file to the study coordinator.

Progress is stored locally in the annotator's browser. The page does not send
annotations to a server.

## Publication boundary

The package contains only the public audit context. It does not contain private
gold references, original SUMO/OSM files, API credentials, or unpublished raw
inputs. Do not add any of those materials to this directory.
