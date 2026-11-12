# Horologe - Devlog

Static markdown dev diary. No build step.

## Run locally
    python3 -m http.server 8000
then open http://localhost:8000

## Add a post
1. Create posts/<slug>.md starting with:
   ---
   title: My title
   date: 2026-11-12
   tags: tag1, tag2
   summary: One line shown on the list page.
   ---
2. Add "<slug>" to posts.json
3. Images go in posts/images/, referenced as ![alt](images/file.png)
