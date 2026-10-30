# SFGO - A go based Salesforce CLI

## What

SFGO is a planned Go implementation of a small subset of the Salesforce CLI (`sf`). It is tailored to my workflow, not intended to replace `sf`.

## Why

On my Windows work laptop, even `sf -v` takes over 7 seconds and can approach 30 seconds under load. Default plugins take roughly 300 ms each to load there, compared with about 5 ms each on MacOS. My best guess is Windows Defender scanning and its Windows :)

I also want to explore few ideas for better and faster local source tracking.

## How

- Implement only the `sf` features I use.
- Route unsupported features to `sf`.
- Experiment with local source tracking and deployment.
