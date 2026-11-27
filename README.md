## Lim Liang Zhou

Computer Science student at SIT-DigiPen Singapore, in the Real-Time Interactive Simulation programme. Looking for a 12-month software engineering internship, available May 2028 to May 2029.

I work mostly in **C++** and **Python**, and most of what I build is performance-sensitive: routing, ranking, simulation, rendering.

### What I'm building

**Jemz** (formerly SGGotWhat?) - a multi-trimester team app that surfaces events and lesser-known places around Singapore. C++20, running on phones as WebAssembly, with Firebase for sign-in, data and push notifications. *(team repo is private; my modules are in [jemz-modules](https://github.com/limlz/jemz-modules))*

My work on it:

- **Recommendation engine** - seeded k-means persona clustering, boosting spots that similar users engaged with, with a reserved share of results for exploration picks from nearby clusters. Precision@10 up 11% over the previous version on 10,000 synthetic users.
- **Itinerary solver** - exact quickest visit order via Held-Karp dynamic programming up to 12 stops (2-opt beyond that), over real walking, bus and MRT times from OneMap, plus a day planner.
- **Ranking and spatial search** - deterministic weighted scoring with incremental re-ranking. Nearby search answers in 0.4 ms (p95) across 10,010 spots on a Pixel 9a.
- **Server recompute** - clustering and trending moved to a scheduled job on the team's Linux server, publishing one model to Firestore for every client.
- **Submission validation** - GPS checks against Singapore's land outline, rate limits and account-age checks on user-submitted spots.
- **Tooling** - CMake setup, benchmarks, determinism tests, Discord build notifications.

### Public work

| Repo | What it is |
| --- | --- |
| [jemz-modules](https://github.com/limlz/jemz-modules) | **My modules from Jemz** - seeded k-means personas, the collaborative boost, sliced recompute, the Held-Karp itinerary solver and Singapore geo checks, with 39 tests. Builds on its own. |
| [EarlyBirdGetsDaWorm](https://github.com/limlz/EarlyBirdGetsDaWorm) | **Echoes of the Ward** - psychological horror game in C++ on AlphaEngine. Anomaly-hunting in a hospital ward with a boss encounter. I wrote the game state manager, config hot-reload and dynamic lighting. |
| [Game_Project](https://github.com/limlz/Game_Project) | **WEWASHPl8** - dishwashing arcade game in C with CProcessing. I wrote the bubble particle system, the roomba and dirt entities, and the money, sounds and debug code. |

### Background

Before SIT I took a Diploma in Cybersecurity & Digital Forensics at Nanyang Polytechnic, and interned at **IHiS**, Singapore's national healthcare IT agency, where I built a digital nursing audit form in JavaScript against the SharePoint REST API. It went live at Khoo Teck Puat Hospital and replaced a paper process for its nursing staff.

I also served two years as a Supply Supervisor in the Singapore Armed Forces, leading a team of 5 through daily logistics operations.

### Currently

Operating Systems, Data Structures, and computer graphics - rasterization, texture mapping and transforms in OpenGL. Reading a lot of modern C++: RAII, move semantics, ownership, the STL algorithms.

### Contact

Hiring software engineering interns for 2028? Email me at l.liangzhou@digipen.edu, or find me on [LinkedIn](https://www.linkedin.com/in/lim-liang-zhou/).
