# Fab Gym: the three-minute video, in character

You play **Lou Latency**, the robot CEO of a chip fab, showing off his fab and its digital twin. Dry, a little vain,
always loading. Lou's lines are about 430 words, about 2:50 at a calm pace, which leaves room for the music and the cuts.

Each beat names a Meta model at the moment it does something on screen: that is the 25% of the score for Meta tooling.
The **Ready?** column says whether the footage exists today.

| Time | On screen | Lou says | Ready? |
| --- | --- | --- | --- |
| 0:00 | The 3D fab: a slow drone shot over the campus, then Lou walking toward the camera | "Hi. I'm Lou Latency, CEO of a chip fab. Sorry for the wait, I'm still loading. So is my fab, to be honest. My wafers spend most of their childhood waiting in line." | Yes (3D fab; Lou's camera fix is not yet checked on screen) |
| 0:15 | The browser Floor at 12× speed; hover a polisher showing *Gassed* | "I've got 1,043 machines. Every time one comes free, somebody picks which lot goes next. The rush order? The one that's waited nine hours? The one on a timer that gets scrapped if it's late? We make that call thousands of times a day, on rules of thumb, and find out weeks later if we were right." | Yes |
| 0:38 | Title card: **Fab Gym**, the twin | "So I built a twin of my fab. Same machines, same routes, simulated exactly. And I staffed it with Meta's models." | Make the card |
| 0:48 | The ask bar: type a question; the scenario with *said* and *assumed*; a rule as Rust; the scored card | "I ask in plain words. **Muse Spark Open**, Meta's open-weights model, turns my question into an experiment and writes the rule as code. The code runs in a sandbox, the twin races it against my old rule on the same luck, and the card shows only the simulator's numbers, with error bars. I sign, or I don't." | Yes (a live answer needs the Baseten key; otherwise say "a recorded example") |
| 1:15 | The supervisor result on the site, or the Evidence page | "On my training fab, **Muse Spark** checked in once a day and got 117 more wafers a day out than my old rule." | Yes (the site's table) |
| 1:25 | The 3D fab: type "Where do wafers get polished?"; the bubble; Lou walks the visitor to the polishing bay | "In the 3D twin, Muse Spark Open is my brain. Big upgrade. Ask me where wafers get polished and I'll answer from the live run and walk you there. Every number I say comes from the simulator. I'm not allowed to make things up. Believe me, I've tried." | Needs one recording with the key (the end-to-end test passed on 4 Nov) |
| 1:50 | The Build page: Challenge 1, then **Let the AI try** and its move log | "Think you can lay out a fab better than me? Draw one. **Muse Wonder** will race you, with the same moves you've got." | Yes |
| 2:02 | The Floor: click a machine; the coach card answers | "And when a line looks long, click the machine. **Muse Glimmer**, Meta's other open model, runs on our own server and tells you why. For free. My favourite price." | Needs the tunnel to the Linux server up |
| 2:15 | The Evidence page; stop on **120 / 120** | "Clever is cheap. So every scored run gets a receipt, and a referee written in Lean checks it. 120 runs, about 423 million machine jobs, all passed. And when the AI didn't beat my old rule on the big fab, we said so." | Yes |
| 2:35 | The film *Sand to Chip*: 12 seconds, Grain in the quarry, lithography, the chip dancing | "Every fab needs a cinema. **Muse Image** drew this film, and Muse Spark wrote the shots and composed the score, for full orchestra. I have a cameo. It's tasteful." | Yes (from the film file; the cinema screen still shows the old film) |
| 2:50 | Closing card over the building | "Fab Gym. Meta's models propose, my twin scores, Lean checks, and I sign. By Chetnova: an operating system for your full org. Now if you'll excuse me, I have a polisher to motivate." | Make the card |
| 2:58 | Fine print, two seconds | (silent) *Lou is a cartoon. His fab is the SMT2020 testbed, a published research model. No real fab's data.* | Make the card |

## Lines to keep exact

- 1,043 machines; 117 more wafers a day (95% interval 111.5 to 122.5, on a teaching fab of our own); 120 of 120 runs;
  about 423 million machine jobs. Don't round these differently on screen.
- Say "my training fab" for the 117 result: it is the teaching fab, not the full SMT2020 fab.
- Never say a real fab, TSMC, or that the AI runs the fab. Lou's fab is fiction, and the fine print says so.

## Words to avoid

"Real fab", "guaranteed", "runs a fab", any placing or prize before it is announced.
