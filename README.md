## Hi, I'm Maitê

Software engineer in Londrina, Brazil. I build production systems in Python, Node.js and PostgreSQL, with AI coding agents in the loop every day.

Self-taught. I started by automating my own work at an insurance billing desk and kept going until it became the job.

### What I work on

- **Computer vision on outdoor media:** real-time pipelines over camera streams that count people and vehicles and measure attention on LED panels, without storing personal data.
- **Multi-tenant SaaS:** a CRM pulled out of a monolith and turned into a product, with per-tenant schemas, a home-grown automation engine and live updates.
- **AI tooling:** custom MCP servers that expose internal systems (PostgreSQL, ERP APIs, an LED media panel) as agent tools, with scoped permissions and audit logs. Local models via Ollama when data can't leave the network.
- **Internal tools:** 10+ in the last six months, mostly replacing spreadsheet-and-copy-paste workflows for operations teams.

### Selected projects

**ExpoTimeOut**: live inference on outdoor LED media  
Counts people and vehicles, estimates age range and attention time, and runs an activation where visitors generate AI artwork that reaches the panel via QR code in under a minute. The hardest part was infrastructure, not models: cameras with no reachable RTSP endpoint, solved with RTMP push ingest.  
`Python` `YOLO` `ByteTrack` `InsightFace` `FastAPI` `PostgreSQL`

<p align="center">
  <img src="assets/expotimeout.gif" width="260" alt="LED panel at an expo booth showing a live count of people in front of it, average age, and vehicle impressions">
  <br>
  <sub>Live audience count on the panel at an expo booth.</sub>
</p>

**Multi-tenant CRM**  
Schema-per-tenant isolation in PostgreSQL, an automation engine with an expression parser written from scratch (no `eval`), full-text search, and real-time updates over SSE with `LISTEN/NOTIFY`.  
`Node.js` `Express` `PostgreSQL` `React` `Docker` `Caddy`

**AI financial copilot**  
A chat agent that answers financial questions from real ERP data and acts through function calling: reconciling invoices, drafting contracts. Nothing financial runs without human approval plus 2FA, and every action lands in an append-only audit log.  
`Fastify` `React` `RAG` `OAuth2` `ETL`

### Stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,ts,js,nodejs,express,fastapi,postgres,sqlite,opencv,react,vite,tailwind,docker,linux,git&theme=dark">
  <img alt="Python, TypeScript, JavaScript, Node.js, Express, FastAPI, PostgreSQL, SQLite, OpenCV, React, Vite, Tailwind CSS, Docker, Linux, Git" src="https://skillicons.dev/icons?i=py,ts,js,nodejs,express,fastapi,postgres,sqlite,opencv,react,vite,tailwind,docker,linux,git&theme=light">
</picture>

Also: Fastify · MySQL · Java · YOLO · ByteTrack · InsightFace · Claude Code · MCP servers · Ollama · RAG · systemd · Caddy · PM2

### Now

- Software engineer at Intermidia
- BSc in Systems Analysis & Development at Estácio
- Running [Doin Labs](https://doinlabs.com.br): landing pages, automations and applied AI for small businesses

### Contact

[LinkedIn](https://linkedin.com/in/maitedoin) · maitedoin@gmail.com
