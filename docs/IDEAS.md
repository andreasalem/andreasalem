# What this repo is for

`andreasalem/andreasalem` is GitHub's special profile repo: its `README.md` is
shown at the top of github.com/andreasalem. It is **public**: never put
anything here that is private to a project, a lab, or a dataset.

## Already here
- `README.md`: the profile page.
- `assets/chicago-skyline.svg`: the animated banner. One 30 s day over Lake
  Michigan: sunrise over the lake, office lights at dusk, Navy Pier's wheel,
  antenna beacons. Plain SVG with SMIL animation, no scripts (GitHub strips
  those). The colours by hour sit in the `values` lists, keyed by `keyTimes`.

## Ideas for later
- **Pinned work**: a short "Research" section linking papers, the PES
  meta-analysis book, or replication packages once they are public.
- **Skyline**: `gh skyline -o skyline.stl` and commit the STL; GitHub renders
  STL files as a 3D viewer in the browser.
- **Stats cards**: `lowlighter/metrics` (an Action, like the snake) for
  languages, activity, and a contribution calendar.
- **Dotfiles / setup notes**: public parts of the terminal and Claude Code
  setup, for reuse on a new machine.
- **Templates**: issue and PR templates in `.github/` here do NOT apply to
  other repos; only a repo named `.github` does that.
- **Talks / CV**: a PDF CV or slides, linked from the README.

## Notes
- The contribution snake (Platane/snk) was tried and replaced by the skyline on
  2026-10-24; its workflow is in git history and its images on the `output`
  branch.
