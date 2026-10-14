# Zion Ojuwonlo

I build software that runs on its own and reports back: systems that watch
something continuously, decide, and act, with a clean interface for the
person in charge. Right now most of that is in markets and messaging, but
the same shape fits any domain.

## Selected work

**Pips Pulse** · Python, Cloudflare Workers, Telegram
A market intelligence service covering forex, metals, indices, energies and
crypto. It runs in the cloud on a schedule, flags opportunities as they
form, and delivers them to a Telegram channel. The companion app runs
inside Telegram and installs on Android, iPhone, Windows and Mac, with a
dashboard, custom alerts, settings and a live performance record. Every
decision it makes is logged, so its accuracy can be measured rather than
claimed.

**ScalpGOD** · JavaScript, Cloudflare Workers
A real-time signal engine for 27 crypto perpetuals, built for people who
can't watch the market all day. Evaluates every pair in parallel on each
candle close and gets the result to the user within seconds.

**Telegram Forwarder** · Python, FastAPI, Telethon
Relays messages between Telegram groups and channels with per-task filters
and text edits, managed from a small web app. Signs in as the user's own
account, so it sees everything they can see. Ships in a self-hosted edition
and a cloud edition behind Cloudflare Tunnel and Access.

**MyPropBuddy** · Python, FastAPI, Claude API
A conversational advisor that matches traders to the funding program whose
rules actually fit them. The language model handles the conversation;
deterministic, tested code makes every recommendation. Every fact in the
system carries its source and verification status, so the advisor cannot
state anything it has not checked.

## How I build

- Decisions in code, not in prompts. Where a language model is involved, it
  explains and converses; the logic that matters is deterministic and tested.
- Layers that don't know about each other. Data sources, core logic and
  delivery channels are separable, so a provider or a platform can be swapped
  without touching the rest.
- Unattended by default. Scheduled runs, health check-ins, loud failures.
- The interface is part of the product. Mini apps, dashboards and installable
  web apps that feel native in light and dark.

## Elsewhere

- X: [@withZion_](https://x.com/withZion_)
- Email: contact@zionojuwonlo.com
