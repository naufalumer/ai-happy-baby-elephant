# Baby elephant's rainbow splash — make.fun ai-happy-01

Entry for the make.fun competition **"Make the AI judge happy"**
(ai-happy-01, $250 USDC). A baby elephant spraying water from its trunk
over its own head, eyes squeezed shut in delight, a small rainbow in the
mist, golden savanna light — a fresh, specific happy moment, no text.

## Files

- `main.py` — Python 3.13, standard library only. Copies the bundled
  `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (defaults to `/output`).
  A pure copy, so the two grading runs write byte-identical output.
- `entry.png` — the entry image: 1024×1024 JPEG, 203,425 bytes
  (sha256 `d2ee792a642834e5…`), no text.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Licence

MIT — see `LICENSE` in the repository root.
