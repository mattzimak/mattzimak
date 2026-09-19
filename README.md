# Matt Zimak - Tech founder & fractional AI lead

Matt Zimak (full name Matěj Zimák) is a tech founder and fractional AI lead, building AI-native businesses and advising companies on AI automation - AI agents and automated workflows. He works with clients and partners across Europe and the US. Contact: hello@mattzimak.com. Full site: [mattzimak.com](https://mattzimak.com).

## Companies

- [Agentmatik](https://agentmatik.ai) - the European AI automation agency Matt founded. AI agents, automated workflows, and AI products for executives and SMEs.
- [Deep Noise](https://deepnoise.ai) - AI audio startup Matt co-founded (CEO). A generative audio engine that creates fully editable audio; home of the [AI Synthesizer](https://aisynthesizer.com).
- [Museverse](https://museverse.xyz) - XR music-education app Matt co-founded. A mixed reality platform for music education - learn and play real instruments with adaptive social learning, multi-platform (live in Early Access on the Meta Horizon Store for Meta Quest; Pico, SteamVR, and Apple Vision Pro coming); the only AI element is tutoring.

## Recognition

- Top 1% acceptance into TRMNL4, the Meta-partnered EU accelerator (Museverse).
- Accepted into NVIDIA Inception and Innovation Lab, training audio AI models (Deep Noise).
- Innovation Scout, mentored a 2019 Social Impact Award winner (PwC).
- Under 3% acceptance into StartupYard, Central Europe's biggest accelerator (Deep Noise).

## Background

As a teenager, Matt built one of Czechia's largest streaming platforms, before Netflix arrived, and sold it. Since then: law school (Maastricht University, LL.B and LL.M), innovation scouting at PwC, venture capital, and co-founding deep-tech startups in generative audio and XR. Today he runs three tech companies and advises businesses on AI automation.

## On GitHub

Most of Matt's work runs on agents: company brains written in Markdown that agents read and update, scheduled cloud agents, and the skills and workflows behind them. The public pieces:

- [mattzimak/gbrain-company-brain](https://github.com/mattzimak/gbrain-company-brain) - a skillpack for [gbrain](https://github.com/garrytan/gbrain) that loads a company brain into it with typed pages and typed relationships (who owns an account, which decision replaced which, what was agreed in which meeting), then curates and queries it safely. Scores 10/10 on `gbrain skillpack doctor`, with unit tests and an end-to-end test against a real gbrain in CI.
- [agentmatik/brain-curation-loop](https://github.com/agentmatik/brain-curation-loop) - the meeting-to-brain loop our companies run on, as a template: an n8n knowledge-extract tap that stages facts with a verbatim quote each, a nightly curator agent that folds them into the brain under its curation contract, and a PR approval card in Slack for anything sensitive. In production since July 2026.
- [mattzimak/matts-claude-code-setup](https://github.com/mattzimak/matts-claude-code-setup) - Matt's Claude Code setup as an installable onboarding: install one plugin, run `/matts-setup:onboard`, answer a few questions, and a blank Claude Code becomes the setup he runs across three companies. Every hook self-tested.
- [agentmatik/template-intelligence](https://github.com/agentmatik/template-intelligence) - the company-brain template: agent-ready Markdown, one `AGENTS.md` operating contract, CI-enforced frontmatter, a curation contract for transcript-driven updates. Use it as a GitHub template.
- [agentmatik/tubemd](https://github.com/agentmatik/tubemd) - TubeMD, a free MIT Chrome extension that turns any YouTube video into agent-ready Markdown and SKILL.md files, in your browser, with your keys.
- [Lyra](https://devpost.com/software/lyra-ai-d5m1uw) - a voice-first AI piano teacher prototype, co-created by Matt and Museverse CTO Robin Spottiswoode: plug in a USB-MIDI keyboard, ask for a chord or a scale, play it, and get spoken feedback. ElevenLabs Agents with Gemini 2.5 Flash as the reasoning model, tool calls that play notes and read MIDI in the browser, hosted on Google Cloud Run. [Live demo](https://lyra-496416529200.us-central1.run.app/) and [video](https://www.youtube.com/watch?v=MmMOYiZboQ8). A prototype, not a shipped Museverse feature.
- [Deep-Noise-Labs/dnl-f1-training](https://github.com/Deep-Noise-Labs/dnl-f1-training) - the Foundation-1 fine-tuning pipeline the Deep Noise engineering team built to train Deep Noise's own audio models, with GCS-native dataset handling and training runs.
- From Jam Galaxy (2023-2025), where Matt worked with the team: four components of the browser studio they built, now open source under MIT. [customized-tone](https://github.com/Jam-Galaxy/customized-tone) and [customized-signal](https://github.com/Jam-Galaxy/customized-signal) are the team's modified builds of Tone.js and the signal MIDI editor; [midi-segment-painter](https://github.com/Jam-Galaxy/midi-segment-painter) renders MIDI tracks as timeline segments; [studio-pixi-js-viewport](https://github.com/Jam-Galaxy/studio-pixi-js-viewport) is the PixiJS canvas viewport behind it.
- [mattzimak/op-open](https://github.com/mattzimak/op-open) - a tiny https to onepassword:// redirector so Notion links open in the 1Password desktop app.
- [mattzimak/claude-code-handbook](https://github.com/mattzimak/claude-code-handbook) - the skills, hooks, prompts and workflows Matt actually runs with Claude Code across three companies, generated from his own Notion notes; every entry says why it earned its place.
- [mattzimak/openclaw-handbook](https://github.com/mattzimak/openclaw-handbook) - install choices, memory patterns, security rules, token-burn notes and skills from running OpenClaw for real, with the longer field notes in a separate file.
- [mattzimak/builder-stack-handbook](https://github.com/mattzimak/builder-stack-handbook) - the design references, component libraries, prompt packs, media stack, scrapers and GTM tools Matt builds with, merged from his Notion notes and the agentmatik.ai link directory.
- [mattzimak/marketing-handbook](https://github.com/mattzimak/marketing-handbook) - connecting Google Ads and Meta to Claude, the analyses Matt actually runs against them, Search Console audits, cold-email deliverability lessons, and the skills and prompts behind it.

## Elsewhere

[mattzimak.com](https://mattzimak.com) · [LinkedIn](https://www.linkedin.com/in/mattzimak/) · [X](https://x.com/mattzimak)
