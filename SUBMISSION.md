# The submission form, a draft

For the Cerebral Valley form. Indie track, theme Push the Frontier. Paste, then adjust.

**Project name:** Fab Gym, by Chetnova

**One line:** Lou Latency runs a chip fab and tests every decision on its digital twin first: Meta's models write the
rules, guide you through the fab and play against you; the simulator scores them; a Lean referee checks every run; a
person signs.

**What it is:** A digital twin of a 1,043-machine wafer fab on the published SMT2020 testbed, presented in character by
its robot CEO, Lou Latency. It's a Rust simulator (about 0.03 s per simulated day), in the browser through
WebAssembly, and a walkable 3D fab in Godot. You can watch the whole fab live, draw your own and race the AI, build one from a
napkin sketch, or walk the 3D fab while Lou answers questions and takes you where the answer is.

**How it uses Meta's models:**
- **Muse Spark Open** (open weights, on Baseten): turns a plain-English question into a scenario that must pass a
  schema, with every value marked said or assumed. It writes dispatch rules as Rust, compiled to WebAssembly,
  sandboxed and scored on held-out seeds, and reads the scores and rewrites the rules. It is also Lou's brain in the
  3D fab: answers from the live run, walking to the right bay, what-ifs scored by the simulator. Every number Lou says
  is checked against the simulator's facts.
- **Muse Spark 1.3**: supervises the fab day by day. On our teaching fab it got 117 more wafers a day out than today's
  rule (95% 111.5 to 122.5), for $0.077 over 302 calls. It also reads a photo of a fab drawn on paper into a layout, and it wrote the
  film's shot list and composed its 12-cue orchestral score.
- **Muse Wonder**: the opponent in Race the AI, playing build challenges with the same ten moves as a player.
- **Muse Image**: the whole cast (11 kinds of machine in 10 moods each, the wafer, the lots, Lou), posters, glossary pictures, and the 827
  pictures of the 3:38 film *Sand to Chip*.

**Impact:** A fab can't try a new rule for its floor without risking weeks of output. Fab Gym tests it first, says
how sure it is, and explains it in words a newcomer follows. The same machinery is Chetnova's: an operating system for
an organisation.

**Technical depth:** an exact event-log match against a reference engine; paired seeds with 95% intervals; a
pre-registered uncertainty study; a WebAssembly sandbox with a fuel limit; a Lean 4 referee with soundness proofs that
passed all 120 scored runs (about 423 million machine jobs) and rejects tampered copies. We report where the AI lost:
on the full fab over 60 days, no policy beat today's rule.

**What's new:** everything in the repository was built after the 26 October kickoff. Earlier work is labelled in the
README's "What is new in this hackathon".

**Links:** the site (this repository's Pages), the code (github.com/apoorvasinha183/fab-gym), the video (YouTube).
