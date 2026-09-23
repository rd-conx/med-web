# Mix Evaluation Dataset - web

A browser for the Mix Evaluation Dataset: listening-test evaluations of different
mixes of the same songs, with in-browser audio comparison. It collects
**20 songs / 205 mixes / 5,473 evaluations**, where each evaluation is a
listener's rating (and often a written comment) of one mix.

Each song was mixed several ways by different engineers, listeners rated those
mixes in controlled sessions across several institutions. The browser lets you
pick a song, see its mixes ranked by mean score, audition them, and read the
individual ratings and comments behind each one.

Scores carry a ±1 standard-error whisker, because with between 5 and 76 raters
per mix the top few are often not separable — overlapping whiskers mean the
listening test did not actually distinguish those mixes. Each mix also shows
**what listeners talked about**: every rating comment in the dataset was
hand-annotated into statements tagged with an instrument, a mix feature, and a
valence (12,842 statements across 4,659 comments), and those tags are tallied
per mix so a score comes with the reasons listeners gave for it.

That annotation pass never covered the 2017 sessions (CNS and QUT), and it
missed two further sessions, so 583 comments carry no tags (560 of them CNS and
QUT): 24 mixes have no topic summary and 31 more summarise
only part of their comments. The browser says so on each affected mix rather
than showing an unexplained blank — the comments are all still there to read.

## Copyright & licensing

Audio is published for **all 20 songs**, so every mix with a source recording is
playable here. Of the 20 songs:

- **12 are Creative Commons** (BY 3.0 or BY-NC 4.0). The **BY-NC** titles are free
  to share with attribution but restricted from commercial use.
- **6 are copyrighted** and **2 have unknown/undocumented rights.** Their audio is
  included here alongside their ratings and comments. Reusing or redistributing
  these recordings may still require clearance from the respective artists/labels —
  their appearance in this browser does not grant any licence.

As a result, 204 of the 205 mixes have playable audio here (the one remaining mix
has no source recording in the dataset).

Four songs previously listed a bare `McG-pro` mix alongside a numbered
`McG-pro1`/`McG-pro2`. The two renders are byte-identical — the bare name is a
duplicate of the numbered one, and only the numbered mix was ever rated — so
they are now folded together. That is the difference between 209 mixes and 205,
and it is why every mix here is now a rated mix.

Attribution and licence for each song are shown in the browser and come from the
Open Multitrack Testbed and Shaking Through (Weathervane Music). Please respect
each song's licence, including the non-commercial clause where it applies, when
reusing any audio.

## Reference

The dataset is described in:

Brecht De Man and Joshua D. Reiss, "The Mix Evaluation Dataset," in *Proceedings
of the 20th International Conference on Digital Audio Effects (DAFx-17)*,
Edinburgh, UK, September 5–9, 2017.
[[PDF]](https://www.dafx.de/paper-archive/2017/papers/DAFx17_paper_49.pdf)

```bibtex
@inproceedings{deman2017mixevaluation,
  title     = {The Mix Evaluation Dataset},
  author    = {De Man, Brecht and Reiss, Joshua D.},
  booktitle = {Proceedings of the 20th International Conference on Digital Audio Effects (DAFx-17)},
  address   = {Edinburgh, UK},
  month     = sep,
  year      = {2017}
}
```
