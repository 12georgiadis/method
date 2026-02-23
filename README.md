## Method

Notes on practice from a filmmaker working with AI, gaming engines, and post-internet aesthetics.

This is not a tutorial. Not a framework. Not a manifesto in the traditional sense. It's a working document that reflects how I think about making films and art with machines -- and why "with" is already the wrong word.

### Position

**Alteration over augmentation.** I don't use AI to do things faster or better. I use it to displace my own thinking -- to see connections I wouldn't see alone, to produce what wouldn't exist without the friction between human intent and machine behavior. The goal is not optimization. The goal is displacement.

**Post-documentary.** My films start from real events, real people, real archives. But the treatment is hybrid: gaming engines, deepfakes, generative images, found footage from virtual worlds. The boundary between document and fabrication is the subject itself.

**Liquid writing.** Not a method in the academic sense. A way of working where research, writing, image-making, and tool-building happen simultaneously, contaminating each other. The film emerges from the process, not from a screenplay.

**AI as subject, not just tool.** The technology is never neutral in my work. When I use a generative model, the artifacts, the hallucinations, the biases are part of the film. The machine's failures are as valuable as its successes.

---

### Influences

Films, books, artists, and thinkers that shaped this practice. Not a ranked list -- a map of connections.

#### Cinema & moving image

| | |
|---|---|
| Harun Farocki | *Parallel I-IV*, *Eye/Machine*. Operational images, gaming as representation. |
| Chris Marker | *Sans Soleil*, *Level Five*. Essay film as research method. Memory as montage. |
| Peter Tscherkassky | *Outer Space*. Cinema's experimental grammar at its origin. |
| Hito Steyerl | *How Not to Be Seen*, *Duty Free Art*. Post-internet image politics. |
| Forensic Architecture | Investigation as aesthetic practice. Spatial and temporal reconstruction. |
| Philippe Grandrieux | *Sombre*, *Un lac*. The body as image beyond representation. |
| Romain Champalaune | *Vie & Mort d'Oscar Perez*. |
| *Mr. Robot* | Fluid identity, paranoia, digital unreliable narrator. |
| *A Scanner Darkly* | Rotoscope as document-fiction boundary. |

#### Art & digital art

| | |
|---|---|
| Gregory Chatonsky | Pioneer of net art and AI art. AI as transformation, not tool -- as profound as the invention of photography. |
| Trevor Paglen | Machine vision, invisible images, AI and surveillance. |
| Peter Burr | Visual patterns through video game engines. |
| Xu Bing | Surveillance footage as artistic material. |
| Mark Lombardi | Narrative structures. Data visualization as investigation. |
| Holly Herndon & Mat Dryhurst | *Holly+*, Spawning. AI as collaborative creative entity. |
| Ian Cheng | *Emissaries*. Autonomous simulations as narrative. |
| Gerhard Richter | Painting at the limit of photography. |
| Francis Bacon | The figure against representation. |

#### Philosophy & theory

| | |
|---|---|
| Roger Caillois | *Les jeux et les hommes*. Classification of play: mimicry, alea, agon, ilinx. |
| Jacques Henriot | *Le jeu*. Philosophy of play as attitude, not object. |
| Vilem Flusser | *Towards a Philosophy of Photography*. Technical images and apparatus. |
| Gilbert Simondon | *On the Mode of Existence of Technical Objects*. Machines are not tools. |
| Donna Haraway | *Staying with the Trouble*. Sympoiesis, making-with. |
| Yuk Hui | *Art and Cosmotechnics*. Technology as culturally situated. |
| Byung-Chul Han | *In the Swarm*. Digital culture and the crisis of narrative. |

#### Video games & interactive

| | |
|---|---|
| *Yume Nikki* | Dream exploration as narrative structure. |
| *Grand Theft Auto V* | Open world as found footage. Source material for *Swatted*. |

#### Literature & journalism

| | |
|---|---|
| Journalism as primary source | "The driving force behind my work is always an encounter, whether with people or by reading an article." |
| Film criticism | The practice began through writing about cinema, not making it. |

> This list is incomplete. It grows with the work.

---

### Research methodology

How I use AI tools for documentary research and artistic production.

#### Tools

**Research & thinking**
- **Claude Code** as primary collaborator — config, workflows, and rationale in [claude-code-workflow](https://github.com/12georgiadis/claude-code-workflow)
- 38 agent personas (filmmakers, philosophers, artists) for structured creative consultation

**Generative production**
- **ComfyUI** for image/video generation pipelines — architecture in [comfyui-cinema-pipeline](https://github.com/12georgiadis/comfyui-cinema-pipeline)
- **Blender VSE + Pallaidium** for AI generation inside the editing timeline (stills → video, ControlNet-guided sequences)
- **LTX-2, Wan 2.2, Flux.2, HunyuanVideo** — current model stack for video generation

**Editing & post-production**
- **Final Cut Pro 12** as primary NLE (assemblage, offline editing, semantic transcript search) — workflows in [fcp-workflow](https://github.com/12georgiadis/fcp-workflow)
- **DaVinci Resolve** for color grading and online conform
- **VoiceInk** for offline voice dictation

**Capture**
- **Magic Lantern / open hardware** for RAW cinema capture — workflows in [open-source-cinema](https://github.com/12georgiadis/open-source-cinema)

**Infrastructure**
- RTX 5090 (GPU inference, ComfyUI), Mac Mini M4 (always-on server, Paris), MacBook Air M3 (primary workstation)
- Tailscale mesh VPN connecting all machines

#### Approach

Research is not a phase that precedes production. Research *is* production.

1. **Accumulate** -- Gather everything. Web archives, court documents, social media traces, news articles, academic papers. Don't filter yet.
2. **Compress** -- Use AI to summarize, cross-reference, find patterns. Sparse priming representations to keep large corpora accessible.
3. **Displace** -- Feed the research back through generative tools. Not to illustrate findings, but to produce new images and connections from them.
4. **Confront** -- Show the machine's output to the human subjects, to witnesses, to experts. The gap between what the AI produces and what people remember is where the film lives.

---

### Current work

**Films**
- *The Goldberg Variations* -- hybrid feature on Joshua Ryne Goldberg and the multiplication of online identities. Villa Albertine 2026.
- *Virus* -- hybrid feature on Mihai Ionut Paunescu and cybercrime infrastructure.

**Next territory**
- Video games with AI — applying the same methodology (post-documentary, liquid writing, alteration over augmentation) to interactive narrative and game worlds.

---

[Website](https://ismaeljoffroychandoutis.com) · [Films](http://filmsgrandhuit.com/en/author/ismael-joffroy-chandoutis/) · [Vimeo](https://vimeo.com/ismaeljoffroychandoutis)
