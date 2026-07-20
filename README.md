# Never Search Alone — Claude Project Setup

This repo contains a ready-to-use Claude Project Instruction set for the **Never Search Alone (NSA)** job search methodology by Phyl Terry. It turns Claude into a step-aware companion for your job search — it knows the five NSA steps, enforces the Mnookin Two-Pager as a hard gate, saves your artifacts to Google Drive with a consistent naming convention, and evaluates your work against real quality criteria at each step.

## How to set it up (takes about 5 minutes)

1. **Go to [claude.ai](https://claude.ai)** and create a new Project (left sidebar → Projects → New Project).
2. **Name it** something like "Never Search Alone" or "NSA Job Search."
3. Open **`NSA-Claude-Project-Instructions.md`** in this repo, select all, and copy it.
4. In your new Project, click **Project settings → Custom instructions**, paste the whole thing in, and save.
5. **Connect Google Drive** to Claude (Settings → Connectors, or you'll be prompted the first time Claude tries to save something). All your artifacts — Two-Pager, CMF, OKRs, interview prep — get saved there automatically as you go.
6. **Create a dedicated Drive folder** for your NSA work (e.g., "NSA Job Search") before your first real session, and have the folder URL ready — Claude will ask for it.
7. **Start a new chat inside the Project** and just start talking. Say something like "let's start" or mention what step you're on (e.g., "I want to work on my Two-Pager") — Claude will onboard you from there.

That's it. You now have your own independent copy — editing your instructions won't affect anyone else's, and vice versa.

## Getting future updates

If Yumi (or whoever's maintaining this repo) pushes an update to `NSA-Claude-Project-Instructions.md`, you'll need to manually re-paste the updated version into your own Project's Custom Instructions — Claude Projects doesn't support auto-syncing from an external URL. Check the commit history on this file to see what's changed and decide if it's worth updating your copy.

## A note on the template documents

The instructions reference several Google Doc templates (Mnookin Two-Pager template, CMF template, Golden Question / Reverse Exit Interview templates, Job Mission w/ OKRs examples, etc.) by their Google Doc ID. These are **not included in this repo** — they're official supplements to the *Never Search Alone* book, owned by Phyl Terry (`pterry@collaborativegain.com`) and, in one case, a Collaborative Gain community member. Claude will try to fetch them on demand when you're actively working on the relevant step. If you hit a permission wall, request access from your JSC facilitator or Collaborative Gain community, or ask Claude to proceed using its built-in understanding of the template's structure instead.

## Disclaimer

The step definitions, quality criteria, artifact naming conventions, and worked examples referenced or summarized in these instructions are derived from the **Never Search Alone** book by Phyl Terry and its supplementary materials, originally maintained on Collaborative Gain's internal Notion workspace and shared Google Drive. This instruction set is an unofficial, community-adapted tool built for personal/JSC use — it is not an official Anthropic or Collaborative Gain product, and it is not affiliated with, endorsed by, or reviewed by Phyl Terry or Collaborative Gain. If you're not already part of a Collaborative Gain Job Search Council or CG program, consider checking out [neversearchalone.org](https://neversearchalone.org) and the original book for the full methodology and context.

Use, adapt, and share within your own JSC as you see fit — just don't represent this as an official NSA/Collaborative Gain resource.
