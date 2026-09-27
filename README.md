# Walk-in Web

Interactive prototype of the "How it works" section for the First Table Walk-ins landing page: a scroll-pinned section with three steps, each with its own animated illustration.

## Run

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 3010
```

## Tweaking

- `TIMING` at the top of the script holds every duration, stagger, spring and scroll value.
- `S` holds each layer's resting state per step, and `TRANSITIONS` holds the order the stages play in.
- Scrolling back up plays the same stages in reverse.

Design source: Figma "D | Walk-ins" (`LxwiVrSMG48wxRFvt1876M`), nodes `8685:410794` and `8664:405191`.
