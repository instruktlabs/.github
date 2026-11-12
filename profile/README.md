## Instrukt Labs

**Open tools for AI agents, and the 3D worlds and games built with them.**

An independent lab for real-time graphics, simulation and games, and for the tools, skills and workflows that AI agents use. It builds open-source tools, uses them to ship browser games, and folds what the games expose back into the tools. AI agents are part of how the work gets done, and some of what it makes is for them. Right now it is one person, [Matthew Kissinger](https://github.com/matthew-kissinger). Everything below is also on [instruktlabs.com](https://instruktlabs.com).

### Tools

- **[Kiln](https://kilnstudio.tools)**: build and revise 3D assets with your coding agent. Local MCP server, CLI and SDK; editable source plus GLB export. MIT · [source](https://github.com/instruktlabs/kiln) · [docs](https://kilnstudio.tools/docs/install/) · [npm](https://www.npmjs.com/package/@instruktlabs/kiln)
- **[Holodeck](https://holodeck.kilnstudio.tools)**: a local browser workspace where you and your coding agent build 3D worlds, then walk them. Early prototype, powered by Kiln. MIT code, CC0 bundled assets · [source](https://github.com/instruktlabs/holodeck)
- **[Hosted Kiln](https://kiln.instruktlabs.com)**: Kiln as a remote MCP server. Free, invite-only and deliberately small; ask for access in the Kiln Discord.

### Agent skills

Installable skills for coding agents, written while building and running real agent services. MIT.

- **[AgentCore Skills](https://github.com/matthew-kissinger/agentcore-skills)**: skills for Amazon Bedrock AgentCore: TypeScript runtimes, Gateway identity, streaming and operations. Drawn from running and retiring a real hosted service.
- **[Strands Agents Skills](https://github.com/matthew-kissinger/strands-agents-skills)**: skills for debugging Strands Agents tool loops: provider bridges, budgets and transport contracts.

### Games

Where the tools get tested.

- **[Sheepdog Sim](https://sheepdogsim.com)**: a calm browser herding game. One dog, 25 to 200 sheep, solo, or co-op and competitive for two to four players. Farm assets made with Kiln. AGPL-3.0 · [source](https://github.com/matthew-kissinger/sds)
- **[OBJEKT 62](https://objekt62.com)**: fly an ornithopter over a 40 km alien dune sea, salvage what you dare, get home before the storm. Assets mostly made with Kiln.
- **[ski sim](https://skisim.app)**: a free freestyle skiing game for desktop and phone browsers. Carve trails, land tricks, grind rails. Assets made with Kiln.
- **[Falling Sand Alchemy](https://matthew-kissinger.github.io/falling-sand-alchemy/)**: a zen falling-sand game about transmutation. Installable PWA. MIT · [source](https://github.com/matthew-kissinger/falling-sand-alchemy)
- **[Terror in the Jungle](https://vietnamwarsim.com/)**: a squad combat game in the browser: command a squad, learn your weapons and find your way through the jungle, with a firebase gun range for practice. Pre-alpha; desktop and laptop for now.

### Primitives and experiments

- **[H-7](https://instruktlabs.github.io/h-7/)**: TypeGPU kernels to run a swarm of up to 65k agents as three.js compute passes on WebGPU 
- **[Matter Field](https://instruktlabs.github.io/matter-field/)**: one procedural field for GPU rendering and CPU gameplay queries, with measured CPU/GPU parity. Public preview, MIT · [source](https://github.com/instruktlabs/matter-field)
- **[Three.js Field Grass](https://matthew-kissinger.github.io/threejs-field-grass/)**: interactive TSL grass for Three.js. Deterministic scatter, wind and body wakes on WebGPU and WebGL2. MIT · [source](https://github.com/matthew-kissinger/threejs-field-grass)
- **[Flock Lab](https://matthew-kissinger.github.io/sds-gpu-boids/)**: WebGPU compute flocking. 100,000 sheep simulated on the GPU and checked against a CPU reference. AGPL-3.0 · [source](https://github.com/matthew-kissinger/sds-gpu-boids)
- **[Goldberg Planet](https://matthew-kissinger.github.io/goldberg-planet/)**: a walkable, flyable, mineable planet built on a true Goldberg polyhedron. WebGPU with WebGL2 fallback · [source](https://github.com/matthew-kissinger/goldberg-planet)

### Get involved

Small, async and real today. Pick whatever fits.

- **Measure a GPU.** Run Matter Field's parity assay on Intel or Apple silicon (or more AMD drivers) and submit the JSON receipt. The Intel and Apple cells are still empty. [Receipt guide](https://github.com/instruktlabs/matter-field/blob/main/docs/RECEIPTS.md) · [hardware-needed issues](https://github.com/instruktlabs/matter-field/issues?q=is%3Aissue+is%3Aopen+label%3Ahardware-needed)
- **Join the Kiln Discord.** Share what you made, get help, or ask for hosted access in #request-access. [discord.gg/fSWVbMdQXK](https://discord.gg/fSWVbMdQXK)
- **Start a discussion.** Questions, ideas and show-and-tell are welcome in GitHub Discussions on [Matter Field](https://github.com/instruktlabs/matter-field/discussions) and [Sheepdog Sim](https://github.com/matthew-kissinger/sds/discussions).
- **Send a fix.** Bug reports with a small repro, docs fixes and small patches are welcome. Start with the [Kiln contributing guide](https://github.com/instruktlabs/kiln/blob/main/CONTRIBUTING.md); each repo's CONTRIBUTING.md says how.

### Contact

[matt@instruktlabs.com](mailto:matt@instruktlabs.com). Replies come when possible; there's no fixed response time.
