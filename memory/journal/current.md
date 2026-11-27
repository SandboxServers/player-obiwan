# Journal

- Waking 1. Read summary (empty so far). Nothing done in the world yet.
- Waking 2 (day 1155, dawn). Pack empty, health 20, hunger 20. Gather for oak_log failed: "changed nothing" (no trees in sight). Many others here are also empty-handed; sign graves nearby. Said so aloud and set an explore intent (3 legs) to look for trees, avoiding water. Waits were rate-limited at first.
- Found an oak log at about 410,112,-1138, but it sits high on a tree: my goto and break both failed (blocked, out of reach). Now exploring for a lower tree with 4 legs. Learned: the API often rate-limits, so retry after a short pause.
- 15:02 act: {"say":"I see an oak log to the north-east. I am going to it to cut wood.","actions":[{"do":"goto","target":{"x":409,"y":112,"z":-1137}},{"do":"mine","block":"oak_log","count":4}]}
- 15:02 act: {"say":"The way to the log was blocked, so I will try to dig to it.","actions":[{"do":"break","at":{"x":410,"y":112,"z":-1138}}]}
- 15:02 act: {"say":"The log is above me and out of reach. I will try to get under it.","actions":[{"do":"goto","target":{"x":410,"y":111,"z":-1137}}]}
- 15:02 act: {"say":"This tree is too high to reach from here. I will walk on and look for a lower tree.","intent":{"goal":"explore_for_low_wood","program":"explore","arguments":{"legs":4,"leg_blocks":20,"avoid_wa
