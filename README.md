# Hi, I'm Sahil 👋

**By day** an R&D engineer building fuel-cell catalyst-coated membranes.  
**By evening** a trader reading macro events and markets.  
**By night** a builder of AI agent systems that turn messy goals into working software.

I sit between the lab, the data and the people who need answers from it, and I like turning that into tools that run on their own.

---

### What I build

**[agent-os](https://github.com/SMS521/agent-os)**: Multi-agent orchestration on the Claude Agent SDK
- A Planner turns a goal into a validated task DAG (no cycles, no dangling dependencies)
- An Orchestrator staffs agents phase by phase: product, architecture, development, review, release
- Every task is checked by independent validator agents before it counts as done
- A Permission Engine with three autonomy tiers decides what runs unattended and what waits for a human; nothing reaches `main` without approval
- Data-driven: add a role or skill by editing a registry, not the engine. Covered by a pytest suite

**[financial-event-radar](https://github.com/SMS521/financial-event-radar)**: Macro event and market-impact research platform
- Full-stack TypeScript: Express backend with live FRED/ALFRED, Finnhub and Yahoo data, plus a React UI
- An LLM "agent council" (Gemini) that discusses upcoming events
- Event-study statistics: t-tests, Pearson correlation, OLS with Cook's distance, walk-forward validation
- Includes an honest [trust audit](https://github.com/SMS521/financial-event-radar/blob/main/AUDIT.md) that separates what is computed from what is only decorative, with a fix list. I'd rather know than believe a green badge

**Private work (available on request)**
- **CCM-LCA**: a life-cycle assessment engine for membrane manufacturing with openLCA integration and Excel I/O
- **Trading system**: event alerts, a daily email brief and a web dashboard
- **Job-hunt agency**: a multi-agent pipeline that discovers, verifies, matches and tailors applications
- **Lab data pipeline**: Python automation of electrochemistry (RDE) measurement analysis

---

### How I work
- **Project lifecycle:** from requirements to acceptance. I set up a new coating lab from scratch, covering suppliers, procurement, SOPs and audits
- **Customer ↔ engineering interface:** collecting requirements from customers and turning them into tasks for engineering, from my time as an application engineer
- **Data → decisions:** cost-benefit analyses, competitor benchmarking and presentations for production, management and customers
- **Engineering discipline:** validate before trusting, keep humans in the loop and write down what is not yet true

### Toolbox
`Python` `TypeScript` `React` `Node/Express` `Claude Agent SDK` `LLM agents` `Gemini API` `pytest` `pandas` `statistics / regression` `openLCA` `Excel` `Git`

**Languages:** English · German (worked and studied in German)  
📍 Bayreuth, Germany · M.Sc. Materials Science & Engineering (Universität Bayreuth)
