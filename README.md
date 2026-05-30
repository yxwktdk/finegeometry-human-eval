# FineGeometry Human Evaluation

This folder is a self-contained static web page for human evaluation on `minitest_500`.

## Files

- `index.html`: evaluation page
- `data/minitest_500.jsonl`: sampled questions
- `images/`: geometry images referenced by the JSONL file

## Local Preview

Run a static server from this folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```

## Collecting Results

Answers are saved in each user's browser `localStorage`. After finishing, the user should click `Export JSONL` or `Export CSV` and send the exported file back to the dataset maintainer.
