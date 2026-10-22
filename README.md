# Casco Digital

Microsoft 365 and infrastructure engineer behind Casco Digital, a managed IT services company in Porto Alegre, Brazil, running since 2012. This account holds the tools I built for that work: PowerShell for Microsoft 365 and Exchange Online, security reporting for small-business clients, and self-hosted automation.

[cascodigital.com.br](https://cascodigital.com.br)

## Focus areas

- **Microsoft 365 and Exchange Online:** mail flow forensics, inbox rule auditing, archiving and MRM, shared mailbox administration
- **Identity and security:** Entra ID, MFA coverage, Secure Score, SPF/DMARC posture
- **Automation:** PowerShell 7, Microsoft Graph REST, Python, Bash, n8n
- **Self-hosted infrastructure:** Docker, Home Assistant, Linux servers, local LLM tooling

## Featured

**[m365-admin-toolkit](https://github.com/cascodigital/m365-admin-toolkit)**: PowerShell scripts for the gaps the admin portals leave open. It correlates trace and quarantine data by MessageId, finds inbox rules that never run, diagnoses mailboxes whose archive is not freeing space, and resets Teams or the new Outlook with a plan-then-apply step. Scripts that change state simulate first by default.

**[m365-report](https://github.com/cascodigital/m365-report)**: a monthly health and security report for each Microsoft 365 tenant, built on Graph REST with app-only authentication. It never shows a number it did not measure.

<a href="https://github.com/cascodigital/bananaphone"><img src="https://raw.githubusercontent.com/cascodigital/bananaphone/main/docs/screenshots/dictate-coach.png" alt="BananaPhone dictating with the language coach" width="640"></a>

**[BananaPhone](https://github.com/cascodigital/bananaphone)**: desktop dictation for IT support. It turns speech in Portuguese, Spanish or English into polished text and Jira notes, and coaches the language you are still learning. Runs on cloud models or fully offline with Ollama and Whisper.

## Repositories

### Microsoft 365 and MSP operations

| Repo | What it does |
|---|---|
| [m365-admin-toolkit](https://github.com/cascodigital/m365-admin-toolkit) | PowerShell toolkit for Microsoft 365, Exchange Online and Windows endpoint administration |
| [m365-report](https://github.com/cascodigital/m365-report) | Monthly Microsoft 365 health and security reports (HTML/PDF) via Graph REST |
| [the-guardian](https://github.com/cascodigital/the-guardian) | Email security audit that scores a domain's SPF, DMARC and MX posture ([live](https://cascodigital.com.br/diagnostico)) |
| [bananaphone](https://github.com/cascodigital/bananaphone) | Dictation to polished text and Jira notes, with a language coach |
| [popup-to-tab](https://github.com/cascodigital/popup-to-tab) | Edge extension that moves popup windows into tabs |

### AI and developer tooling

| Repo | What it does |
|---|---|
| [cockpit](https://github.com/cascodigital/cockpit) | Self-hosted search, daily LLM audit and memory injection for Claude Code, Codex and Gemini CLI sessions |
| [whatsapp-mcp-server](https://github.com/cascodigital/whatsapp-mcp-server) | Local WhatsApp message collector exposed to LLM clients as an MCP server |
| [rolo](https://github.com/cascodigital/rolo) | Taste profile from ListenBrainz history that an AI agent uses to build YouTube Music playlists |

### Self-hosted and home automation

| Repo | What it does |
|---|---|
| [kittlerverse](https://github.com/cascodigital/kittlerverse) | Docker hosts rendered as an interactive galaxy with live telemetry and controls |
| [subtitle-auto-translator](https://github.com/cascodigital/subtitle-auto-translator) | Batch subtitle translation for MKV libraries with Gemini and LibreTranslate |
| [kitchen-cast](https://github.com/cascodigital/kitchen-cast) | Home Assistant and Chromecast kitchen display |
| [b3-portfolio-dashboard](https://github.com/cascodigital/b3-portfolio-dashboard) | B3 stock portfolio dashboard for a TV kiosk |
| [hardmob-monitor](https://github.com/cascodigital/hardmob-monitor) | Token-protected RSS feed of new threads in a deals forum |

### Company

| Repo | What it does |
|---|---|
| [cascodigital-site-2026](https://github.com/cascodigital/cascodigital-site-2026) | Casco Digital website and remote support page on Cloudflare Pages |

All projects are MIT licensed unless noted.
