# Walk-in Web

Interactive prototype of the First Table Dine now (walk-ins) landing page: header, hero with auto-scrolling offer cards and ticker, the scroll-pinned "How it works" section, image strips that drift with scroll, FAQ accordion, get-the-app block and footer.

## Run

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 3010
```

## Tweaking

- `TIMING` at the top of the script holds every duration, stagger, spring and scroll value.
- `S` holds each layer's resting state per step, and `TRANSITIONS` holds the order the stages play in.
- Scrolling back up plays the same stages in reverse.
- `TIMING.page` holds the rest of the page: card and ticker speeds, image strip drift, reveal threshold.

Design source: Figma "D | Walk-ins" (`LxwiVrSMG48wxRFvt1876M`), nodes `8685:410794` and `8664:405191`.
