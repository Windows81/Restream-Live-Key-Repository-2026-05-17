# Restream Live Key Repository 2026-05-17

I've amassed a collection of publicly available Restream livestream keys.

## How to Reproduce
Navigate to GitHub, then use your browser's DevTools to run [`get-test-keys.js`](./get-test-keys.js).

Then, once `"Finished!"` is printed, copy the result.

```js
copy('repo_nwo,stream_key\n'+Array.from(Object.keys(resultDump)).join('\n'))
```

The results from your operation above would be stored in [`test-key-candidates.csv`](./test-key-candidates.csv).

Then download and run [`test-keys.py`](./test-keys.py), making sure to have installed:
- FFmpeg

Paste the lines you just copied into the program's standard input.
