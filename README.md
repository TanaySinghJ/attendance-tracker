# Attendance Tracker

A Python tool that tracks my college attendance subject by subject. It shows the
current percentage for each subject and calculates how many classes I can still
skip while staying above the 75% minimum my college requires.

I'm building this stage by stage and committing as I go.

## Roadmap

- [x] Day 0 — project and repository set up
- [ ] **v0** — subjects hardcoded in the file; print percentage and skip count per subject
- [ ] **v1** — CLI to add subjects and mark classes attended, saved to JSON
- [ ] **v2** — safe-to-skip calculation handled properly, including the already-below-75% case
- [ ] **v3** — move storage from JSON to SQLite
- [ ] **v4** — Streamlit web interface, deployed so there's a live link

## Running it

```
python main.py
```

## Notes

The 75% rule at my college applies **per subject**, not overall — so every
calculation happens subject by subject.
