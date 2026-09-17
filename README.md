# Hi, I'm Chris

Founder and Principal AI Engineer at [autopioniere](https://autopioniere.ai). I build and run production AI agents inside real businesses, forward deployed with the customer. 25 years in software, 15 of them in front of German enterprise customers.

## What runs in production

**Voice agent "Emily".** Live across 16 dealership and brand lines of a German automotive retail group. 600+ inbound calls per month, callback contact data captured in roughly 40% of calls. ElevenLabs and Telnyx (SIP/PSTN). I measure it every month from the call logs: outcomes, contact capture, transfer failures.

**Document automation.** Legally required German vehicle documentation from PDFs, scans and system data. A deterministic workflow with LLM steps for parsing, drafting and a coherence check. A person reviews and releases every document. Manual effort went from roughly 30 to 45 minutes to about 5 to 10 minutes per document (customer estimate).

**autopioniere platform.** Tool first, on Mastra. Every capability exists once as a tool. Chat, mini apps, a browser side panel, voice and an MCP endpoint are surfaces over the same tools. Skills come in two modes: procedures, where code decides the steps and every run is recorded for audit, and playbooks, where the model decides. Anything a human has to sign off runs as a procedure.

**The browser is the API.** Many dealer systems have no open API. A browser extension runs in the user's own session and calls the systems' backend endpoints deterministically. Recipes and parsers are server side data, so a fix is a deploy, not an extension release.

**Models per job.** Hosted frontier models where German legal text and judgment matter. Fully offline open weight models on my own GPU hardware for data preparation, wiki generation and automatic prompt tuning.

## How I work

Evaluation before release: hold out sets, precision and recall thresholds, snapshot tests for prompts. Prompt injection defences that are unit tested. Working software over slideware, and a number on the result.

## Background

First technical hire for Sitecore in Germany (built the DACH market from zero, then EMEA and APAC). Head of Consulting and member of the executive management team at netzkern. Co-founder and CEO of an AI startup. Data & AI consultant and service lead at Macaw for Siemens, Bayer, Henkel, Covestro, Knorr-Bremse, Metro Digital, Vonovia and RWE. Sitecore MVP 2008 and 2016 to 2019.

## Stack

TypeScript, Node.js, Python, C#/.NET · Mastra, Vercel AI SDK, MCP, Claude API · ElevenLabs, Telnyx · PostgreSQL, Docker, Linux, Azure, GCP · vLLM, Ollama

## Contact

[LinkedIn](https://linkedin.com/in/christopher-wojciech) · chris@wojciech.org
