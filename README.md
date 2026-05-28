# AdaState — Project Page

Source for the [AdaState](https://adastate.github.io) project page.

**Paper:** *AdaState: Self-Evolving Anchors for Streaming Video Generation*
**Authors:** [Yusuf Dalva](https://yusufdalva.github.io/), [Pinar Yanardag](https://pinguar.org/) — Virginia Tech

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Layout

```
index.html               # single-page site
assets/                  # framework + motivation figures, hero video, paper PDF
5-sec/, 12-sec/          # within / beyond training-horizon gallery clips
30s-comp1/.../comp3/     # 6× horizon side-by-side comparisons
window-ablation/         # state size & cache window ablation
alpha-ablation/          # horizon weight α ablation
```

`.nojekyll` is present so GitHub Pages serves the files as-is (no Jekyll build).
