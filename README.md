# notmyfault history

This branch is maintained by [notmyfault](https://github.com/tashikomaaa/notmyfault).
It stores the recent outcome of each test, so failures can be told apart: new, flaky or already broken.

- `history/<key>.json`: the history of a test suite.
- `badges/<key>.json`: a [shields.io endpoint](https://shields.io/badges/endpoint-badge) counting its flaky tests.
- `reports/<key>.html` and `index.html`: pages listing its unreliable tests, to publish as a static site.

The branch is rewritten as a single commit on every update. Deleting it simply resets the history.
