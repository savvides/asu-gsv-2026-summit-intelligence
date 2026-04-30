# ASU+GSV 2026 Summit Intelligence

Transcripts, analysis, and session data from the ASU+GSV Summit 2026 (April 12-15, San Diego).

## What's Here

| Resource | Description |
|----------|-------------|
| [Summit Intelligence Report](synthesis/summit-intelligence-report.md) | Thematic synthesis of transcribed sessions. Start here. |
| [Full Session Index](schedule/full-session-index.md) | All sessions with speakers, tracks, tags, and links |
| [ScaleU Sessions](schedule/scaleu-sessions.md) | Sessions flagged as relevant to EdTech validation |
| [Transcripts](transcripts/) | Full session transcripts with speaker metadata, executive summaries, and key quotes |
| [Roundtable Memo](deliverables/roundtable-memo.md) | Synthesis from "What If Universities Stopped Running the Same Pilot Twice?" |
| [Demand Signals](deliverables/demand-signals.md) | Why education leaders are switching -- patterns from five summit panels |
| [EdTech Pilot Playbook](deliverables/edtech-pilot-playbook/) | Evaluation and diagnostic frameworks for EdTech pilots |
| [Video Metadata](video-metadata.json) | Structured data for all transcribed sessions (speakers, URLs, schedule matches) |

## Quick Start

**If you're short on time:** Read the [Summit Intelligence Report](synthesis/summit-intelligence-report.md). It's a 20-minute read covering the six biggest signals from the summit, with thematic deep dives on AI tutoring, assessment, career navigation, EdTech investment, policy, equity, and AI's effect on cognition.

**If you want to understand buyer behavior:** Read [Why Education Leaders Are Switching](deliverables/demand-signals.md). It analyzes what's actually driving adoption decisions, drawn from ten summit panels across two rounds of analysis.

**If you want to explore:** Browse the [Full Session Index](schedule/full-session-index.md). Sessions with a 🎙️ have full transcripts. Sessions with ⭐ were flagged as ScaleU-relevant.

**If you want raw data:** The `transcripts/` directory has sessions with YAML frontmatter (speakers, track, tags, dates, YouTube links). The `video-metadata.json` file has structured data for all transcribed sessions.

**If you want to run the tools:** The `tools/` directory has Python scripts for transcription (`transcribe.py`), enrichment (`enrich-transcripts.py`), and schedule matching (`match-schedule.py`). Install dependencies with `pip install -r tools/requirements.txt`. Requires `ffmpeg` for audio processing and an `OPENAI_API_KEY` environment variable. Override the Whisper model with the `WHISPER_MODEL` env var.

## About

Prepared by Philippos Savvides, Head of ScaleU.

philippos.savvides@asuep.org | [ScaleU.org](https://scaleu.org)

This is a knowledge resource, not an endorsement of any company or product mentioned.

## License

[CC BY 4.0](LICENSE) -- share and adapt with attribution.
