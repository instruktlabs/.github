## Instrukt Labs

**Open tools for building 3D worlds with coding agents, tested in real games.**

An independent lab for real-time graphics, simulation and games. It builds open-source tools, uses them to ship browser games, and folds what the games expose back into the tools. Right now it is one person, [Matthew Kissinger](https://github.com/matthew-kissinger).

### Tools

- **[Kiln](https://kilnstudio.tools)**: build and revise 3D assets with your coding agent. Local MCP server, CLI and SDK; editable source plus GLB export. MIT · [source](https://github.com/instruktlabs/kiln) · [docs](https://kilnstudio.tools/docs/install/) · [npm](https://www.npmjs.com/package/@instruktlabs/kiln)
- **[Holodeck](https://holodeck.kilnstudio.tools)**: a local browser workspace where you and your coding agent build 3D worlds, then walk them. Early prototype, powered by Kiln. MIT code, CC0 bundled assets · [source](https://github.com/instruktlabs/holodeck)
- **[Hosted Kiln](https://kiln.instruktlabs.com)**: Kiln as a remote MCP server. Free, invite-only and deliberately small; ask for access in the Kiln Discord.

### Games

Where the tools get tested.

- **[Sheepdog Sim](https://sheepdogsim.com)**: a calm browser herding game. One dog, 25 to 200 sheep, solo, or co-op and competitive for two to four players. Farm assets made with Kiln. AGPL-3.0 · [source](https://github.com/matthew-kissinger/sds)
- **[OBJEKT 62](https://objekt62.com)**: fly an ornithopter over a 40 km alien dune sea, salvage what you dare, get home before the storm. Assets mostly made with Kiln.
- **[ski sim](https://skisim.app)**: a free freestyle skiing game for desktop and phone browsers. Carve trails, land tricks, grind rails. Assets made with Kiln.
- **[Falling Sand Alchemy](https://matthew-kissinger.github.io/falling-sand-alchemy/)**: a zen falling-sand game about transmutation. Installable PWA. MIT · [source](https://github.com/matthew-kissinger/falling-sand-alchemy)
- **[Terror in the Jungle](https://vietnam-war-sim.pages.dev/)**: a browser combined-arms sandbox set in the Vietnam War, on real elevation data for the A Shau Valley. Infantry, vehicles and aircraft in one Three.js WebGPU runtime. Rebuild in progress.

### Primitives and experiments

- **[Matter Field](https://instruktlabs.github.io/matter-field/)**: one procedural field for GPU rendering and CPU gameplay queries, with measured CPU/GPU parity. Public preview, MIT · [source](https://github.com/instruktlabs/matter-field)
- **[Three.js Field Grass](https://matthew-kissinger.github.io/threejs-field-grass/)**: interactive TSL grass for Three.js. Deterministic scatter, wind and body wakes on WebGPU and WebGL2. MIT · [source](https://github.com/matthew-kissinger/threejs-field-grass)
- **[Flock Lab](https://matthew-kissinger.github.io/sds-gpu-boids/)**: WebGPU compute flocking. 100,000 sheep simulated on the GPU and checked against a CPU reference. AGPL-3.0 · [source](https://github.com/matthew-kissinger/sds-gpu-boids)
- **[Goldberg Planet](https://matthew-kissinger.github.io/goldberg-planet/)**: a walkable, flyable, mineable planet built on a true Goldberg polyhedron. WebGPU with WebGL2 fallback · [source](https://github.com/matthew-kissinger/goldberg-planet)

Field notes: [AgentCore Skills](https://github.com/matthew-kissinger/agentcore-skills) and [Strands Agents Skills](https://github.com/matthew-kissinger/strands-agents-skills), installable coding-agent skills for Amazon Bedrock AgentCore and Strands Agents. MIT.

### Get involved

Small, async and real today. Pick whatever fits.

- **Measure a GPU.** Run Matter Field's parity assay on Intel or Apple silicon (or more AMD drivers) and submit the JSON receipt. The Intel and Apple cells are still empty. [Receipt guide](https://github.com/instruktlabs/matter-field/blob/main/docs/RECEIPTS.md) · [hardware-needed issues](https://github.com/instruktlabs/matter-field/issues?q=is%3Aissue+is%3Aopen+label%3Ahardware-needed)
- **Join the Kiln Discord.** Share what you made, get help, or ask for hosted access in #request-access. [discord.gg/fSWVbMdQXK](https://discord.gg/fSWVbMdQXK)
- **Start a discussion.** Questions, ideas and show-and-tell are welcome in GitHub Discussions on [Matter Field](https://github.com/instruktlabs/matter-field/discussions) and [Sheepdog Sim](https://github.com/matthew-kissinger/sds/discussions).
- **Send a fix.** Bug reports with a small repro, docs fixes and small patches are welcome. Start with the [Kiln contributing guide](https://github.com/instruktlabs/kiln/blob/main/CONTRIBUTING.md); each repo's CONTRIBUTING.md says how.

### Contact

[matt@instruktlabs.com](mailto:matt@instruktlabs.com). Replies come when possible; there's no fixed response time.
