# mit-webtoon-reader

Fullscreen, edge-to-edge webtoon reader shell.

- No comic images are stored in this repo.
- Open with chapter data in the URL hash or `?src=` JSON URL.

Examples:

```
https://snakejohn.github.io/mit-webtoon-reader/?src=https://example.com/chapter.json
https://snakejohn.github.io/mit-webtoon-reader/#c=<base64url-json>
```

JSON shape:

```json
{
  "title": "Chapter title",
  "images": [
    "https://.../001.jpg",
    "https://.../002.jpg"
  ]
}
```
