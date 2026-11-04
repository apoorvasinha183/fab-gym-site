# Fab Gym: the submission site

The page judges land on: Lou Latency's crisis, his cast, his first problem and his studio, with Meta's models doing the
work, and the fab itself, playable in the browser. The code lives in
[fab-gym](https://github.com/apoorvasinha183/fab-gym); its README has the full build and run instructions.

Once Pages is on: **https://apoorvasinha183.github.io/fab-gym-site/**

## What is here

| Path | What |
| --- | --- |
| `index.html` | The site, in Lou's voice. His lines were written by Meta's Muse Spark; every picture was drawn by Muse Image. |
| `play/` | The fab itself: the browser build of Fab Gym (the live Floor, all 1,043 machines simulated in the page, Evidence, Runs, the glossary). Static files, no server. |
| `img/` | The site's pictures: the crisis, the cast on stage, the studio, the posters |
| `SCRIPT.md` | The three-minute video, beat by beat, for Lou to perform |
| `SUBMISSION.md` | The submission form's answers, a draft |

## Three ways to see the fab

| Way | Where |
| --- | --- |
| In the browser, nothing to install | `play/` on this site |
| The 3D fab with Lou, Mac or Windows | [the release](https://github.com/apoorvasinha183/fab-gym/releases/latest) (start the helper first) |
| Everything, on your computer or headless | [fab-gym's README](https://github.com/apoorvasinha183/fab-gym#run-it-three-ways), "Run it: three ways" |

In the browser, Meta's model features show recorded answers; for live answers, run it on your computer with your own
key (bring your own key: `~/.config/fab-gym/meta.key` or `baseten.key`).

## Refreshing `play/`

After a change in fab-gym's `web/`, rebuild it there (`sh web/build.sh`) and copy it here:

```sh
rsync -a --delete --exclude tests --exclude tools --exclude design-review --exclude README.md ../fab-gym/web/ play/
```

## Before it goes live

1. Upload the video to YouTube, then put its id in `data-youtube="..."` on the `#video` box in `index.html`.
2. Make this repository public (GitHub serves Pages from public repositories on the free plan), and fab-gym too.
3. Settings, Pages: deploy from the `main` branch, root folder.

Lou Latency is a cartoon. His fab is the SMT2020 testbed (Kopp, Hassoun, Kalir and Mönch, IEEE TSM 2020); no real
fab's data.
