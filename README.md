## Joey Lu

CS at the University of Waterloo. SWE intern at TELUS, Claude Campus Ambassador at Anthropic. Previously Statistics Canada, Windscribe and Waterloo Aerial Robotics.

[joeylu.ca](https://joeylu.ca) · [LinkedIn](https://www.linkedin.com/in/joey-lu-451329309/) · [Resume](https://joeylu.ca/resume.pdf) · lujoey886@gmail.com

### Highlights

- **Meta Muse Spark Open Kernel Challenge** (private, 2026): custom H200 kernels and SGLang serving work for Meta's Muse Spark Open MoE model. My serving patch on SGLang v0.5.23 runs the model **1.20x faster than stock** on an 8x H200 node with matching output quality and no extra GPU memory. It adds a grouped sm_90 NVFP4 expert kernel (route, gather, and one persistent GEMM + SwiGLU + GEMM launch), validated per rank at startup against Marlin, plus row-sharded prefill projections and DFlash speculative-decoding fixes. CUDA, Triton, Python.
- **[PawTrace](https://github.com/joeyhlu/htn)**: Hack the North winner. Finds missing pets by ranking community sightings with Elasticsearch and running a dog detector on nearby doorbell and CCTV footage. FastAPI, Next.js, YOLOv8.
- **[ValueDex](https://valuedex.ca)**: Pokémon card price history and forecasting, used by 1000+ people. Next.js, FastAPI, scikit-learn, PostgreSQL.
- **[Notion Oracle](https://github.com/joeyhlu/notion-oracle)**: AI assistant for Notion that runs on your existing Claude or ChatGPT subscription. Desktop app for Mac, Windows and Linux plus a browser extension, editing your workspace through a bundled MCP server. TypeScript, Electron.
- **[ProteccAPI](https://github.com/joeyhlu/uofthacks)**: CLI and VS Code extension that blocks commits containing API keys and flags typosquatted packages. 100+ npm downloads. Node.js.
- **[Visualise It](https://github.com/joeyhlu/visualizeIT)**: maps designs onto real 3D objects using pose landmarks, segmentation and homography. Best Mayor's Innovation Challenge at QHacks 2025; now being extended with an offline tracking benchmark. Python, PyTorch, OpenCV.
- **[Stubook](https://github.com/joeyhlu/stubook_master)**: study planner on the [App Store](https://apps.apple.com/us/app/stubook/id6467346995), built with a student team. Flutter.

### In progress

- **Podium** (private): public-speaking practice for Apple Vision Pro. You present inside a Gaussian-splat scan of a real room to an audience that reacts to your delivery. Swift, RealityKit.
- **[CardIQ](https://github.com/cursingparrot4/HT6-Payment-Optimization)**: picks which credit card should pay each recurring bill. An LLM parses your goals; an ILP solver, verified against brute force, does the math. Python, FastAPI, Next.js.
- **Pitch Rush** (private): 1v1 to 4v4 arcade football on Roblox, with every stadium, animation and sound generated in code. Luau.

### Other

[CourseCraft](https://github.com/joeyhlu/coursecraft) · [Quantara](https://github.com/achitaan/Quantara) · [CoTaxAI](https://github.com/joeyhlu/taxchatbot) · [Track Site](https://github.com/joeyhlu/tracksite) · [SoundVeil](https://github.com/joeyhlu/SoundVeil) · [joeylu.ca](https://github.com/joeyhlu/website)

More at [joeylu.ca](https://joeylu.ca).
