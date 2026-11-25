## Instrukt Labs

**Open tools for AI agents, and the 3D worlds and games built with them.**

An independent lab for real-time graphics, simulation and games, and for the tools, skills and workflows that AI agents use. It builds open-source tools, uses them to ship browser games, and folds what the games expose back into the tools. AI agents are part of how the work gets done, and some of what it makes is for them. Right now it is one person, [Matthew Kissinger](https://github.com/matthew-kissinger). Everything below is also on [instruktlabs.com](https://instruktlabs.com).

### Tools

- **[Kiln](https://kilnstudio.tools)**: build and revise 3D assets with your coding agent. Local MCP server, CLI and SDK; editable source plus GLB export. MIT · [source](https://github.com/instruktlabs/kiln) · [docs](https://kilnstudio.tools/docs/install/) · [npm](https://www.npmjs.com/package/@instruktlabs/kiln)
- **[Holodeck](https://holodeck.kilnstudio.tools)**: a local browser workspace where you and your coding agent build 3D worlds, then walk them. Early prototype, powered by Kiln. MIT code, CC0 bundled assets · [source](https://github.com/instruktlabs/holodeck)
- **[Hosted Kiln](https://kiln.instruktlabs.com)**: Kiln as a remote MCP server. Free, invite-only and deliberately small; ask for access in the Kiln Discord.

### Games

Where the tools get tested.

- **[Sheepdog Sim](https://sheepdogsim.com/)** is a browser herding game with 25, 75 or 200 sheep. Play solo or invite friends for co-op or shared-flock competition with two to four players. Farm assets made with Kiln. AGPL-3.0 · [source](https://github.com/matthew-kissinger/sds)
- **[ski sim](https://skisim.app/)** is a browser skiing game with 12 trails, freestyle tricks and rails, online time and freestyle rankings, and multiplayer. Assets made with Kiln.
- **[OBJEKT 62](https://objekt62.com/)** is in development. Fly an ornithopter over a 40 km dune sea, salvage what you dare, and get home before the storm. Assets mostly made with Kiln.
- **[Terror in the Jungle](https://vietnamwarsim.com/)** is a playable desktop pre-alpha, also known as Vietnam War Sim. Command a squad across Riverline or practice at the Firebase Gun Range. Runs best on higher-end hardware.
- **[H-7](https://kilnstudio.tools/play/h-7/)**: a pre-alpha mech evacuation-defense demo. Pilot a heavy walker, defend the outpost relay from the swarm and keep the evacuation shuttles flying; start with Training. Desktop only, with a WebGPU-capable browser. Made with Kiln assets.
- **[Goldberg Planet](https://matthew-kissinger.github.io/goldberg-planet/)**: a sandbox demo on a true Goldberg-polyhedron planet. Explore six worlds on foot in Survival or Creative mode; in Survival, craft a Starfarer and leave the planet. WebGPU with WebGL2 fallback. MIT · [source](https://github.com/matthew-kissinger/goldberg-planet)
- **[Falling Sand Alchemy](https://matthew-kissinger.github.io/falling-sand-alchemy/)**: a zen falling-sand game about transmutation. Installable PWA. MIT · [source](https://github.com/matthew-kissinger/falling-sand-alchemy)

**Game activity as of November 24, 2026.** Sheepdog Sim recorded **13,039 browser profiles** and **1,301 online solo finishes**. Ski Sim recorded **3,544 profiles** and **4,418 accepted online runs**. [Counting details](https://instruktlabs.com/#game-activity).

### Primitives and experiments

- **[Matter Field](https://instruktlabs.github.io/matter-field/)**: one procedural field for GPU rendering and CPU gameplay queries, with measured CPU/GPU parity. Public preview, MIT · [source](https://github.com/instruktlabs/matter-field)
- **[Three.js Field Grass](https://matthew-kissinger.github.io/threejs-field-grass/)**: interactive TSL grass for Three.js. Deterministic scatter, wind and body wakes on WebGPU and WebGL2. MIT · [source](https://github.com/matthew-kissinger/threejs-field-grass)
- **[Sperm Whale Sim](https://spermwhalesim.com/)** is in development. The current preview is a four-minute film about a deep-water hunt, rendered live in the browser.
- **[Ocean Lab](https://matthew-kissinger.github.io/ocean-lab/)** is in development. Steer a gaff-rigged sloop and see how it handles different seas in an interactive Three.js playground.
- **[Flock Lab](https://matthew-kissinger.github.io/sds-gpu-boids/)**: WebGPU compute flocking. 100,000 sheep simulated on the GPU and checked against a CPU reference. AGPL-3.0 · [source](https://github.com/matthew-kissinger/sds-gpu-boids)

### Get involved

Small, async and real today. Pick whatever fits.

- **Measure a GPU.** Run Matter Field's parity assay on Intel or Apple silicon (or more AMD drivers) and submit the JSON receipt. The Intel and Apple cells are still empty. [Receipt guide](https://github.com/instruktlabs/matter-field/blob/main/docs/RECEIPTS.md) · [hardware-needed issues](https://github.com/instruktlabs/matter-field/issues?q=is%3Aissue+is%3Aopen+label%3Ahardware-needed)
- **Join the Kiln Discord.** Share what you made, get help, or ask for hosted access in #request-access. [discord.gg/fSWVbMdQXK](https://discord.gg/fSWVbMdQXK)
- **Start a discussion.** Questions, ideas and show-and-tell are welcome in GitHub Discussions on [Matter Field](https://github.com/instruktlabs/matter-field/discussions) and [Sheepdog Sim](https://github.com/matthew-kissinger/sds/discussions).
- **Send a fix.** Bug reports with a small repro, docs fixes and small patches are welcome. Start with the [Kiln contributing guide](https://github.com/instruktlabs/kiln/blob/main/CONTRIBUTING.md); each repo's CONTRIBUTING.md says how.

### Contact

[matt@instruktlabs.com](mailto:matt@instruktlabs.com). Replies come when possible; there's no fixed response time.
