<div align="center">

<picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/brand/header-dark.svg"><img src="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/brand/header-light.svg" alt="Peter McVries — OSINT researcher, reporter and developer for Indica Independent Media. What Wall Street hoards, we hand back. Free, self-hosted tools for people who cannot buy them, with the method published alongside." width="100%"></picture>

<img src="https://badge.osintnet.uk/badge.svg?dynamic" alt="Indica Independent Media — created with 100% Creative Clarity" width="400">

*No VC. No boss. Just code and conviction.*

</div>

---

## <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/globe-dark.svg"><img src="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/globe-light.svg" alt="" width="22" height="22" align="top"></picture> WarHeatMap

> ### [**warheatmap.app**](https://warheatmap.app)
>
> **Live global conflict intelligence, free.** A world heatmap of conflict events, from Ukraine to
> Gaza to Iran, where every event carries a date, a location, a named conflict, a severity tier and
> **a cited source**. That last field is the whole point: this is a record of events, not a feed of
> headlines.
>
> - **The map.** Heatmap and markers together, filterable by country, tag and severity. Any
>   filtered view is a link you can share.
> - **One page per event.** Every event has its own permanent page with its source, so a single
>   strike can be cited, shared and checked.
> - **Beyond the map.** A stats dashboard, a dedicated Ukraine intel tracker, and live market data
>   alongside the events.
> - **Talk.** The community meets in `#warheatmap` on EFnet, one click away through VoxTerrae.
>
> The most-used thing I have built, live since March 2026, with every change on the
> [public record](https://github.com/indicaindependent/warheatmap/blob/main/CHANGELOG.md).
> **No login, no paywall, no ads, no tracking.**
>
> [Open the map](https://warheatmap.app) · [source](https://github.com/indicaindependent/warheatmap) · MIT

### Live right now

<a href="https://indicaindependent.github.io/warheatmap/"><img src="https://indicaindependent.github.io/warheatmap/live-card.svg" alt="WarHeatMap live status, rebuilt about every 30 minutes from the public warheatmap.app feed: events in the last 24 hours and 7 days, countries covered, severity mix, and the five newest events with their sources." width="100%"></a>

<a href="https://indicaindependent.github.io/warheatmap/"><img src="https://indicaindependent.github.io/warheatmap/live-map.svg" alt="The last 7 days of WarHeatMap events plotted on a world map and coloured by severity: critical, high, medium, low." width="100%"></a>

These two images rebuild themselves about every 30 minutes from the public WarHeatMap feed. Click either one
for the **[mini map](https://indicaindependent.github.io/warheatmap/)**: filter by severity and event type, open any event and its source. It reads the
feed live in your browser, with no login and no tracking.

### What is on the map

Figures below are **measured from the live site on 2026-09-20**, not estimated. Type and severity
shares come from reading a random sample of **260 of the 6,983** event pages, so they are
proportions rather than totals.

| Event type | Share | | Event type | Share |
|---|---:|---|---|---:|
| Airstrike | 18.5% | | Terrorism | 4.6% |
| Diplomacy | 13.5% | | Humanitarian | 3.5% |
| Ground battle | 11.9% | | Infrastructure | 3.5% |
| Missile | 10.4% | | Sanctions | 3.1% |
| Protest | 9.2% | | Explosion | 1.9% |
| Naval | 8.1% | | Assassination · border · cyber | 1.5% / 1.5% / 1.2% |
| Other | 6.9% | | Migration · nuclear | 0.4% / 0.4% |

| Severity | Events | Share |
|---|---:|---:|
| CRITICAL | 32 | 12.3% |
| HIGH | 138 | 53.1% |
| MEDIUM | 80 | 30.8% |
| LOW | 10 | 3.8% |

**Sourcing is the differentiator.** Those 260 events cite **168 distinct outlets** — Al Jazeera,
Reuters, Associated Press, UN News, Kyiv Independent, Sudan Tribune, Anadolu Agency, The Hindu,
Taiwan News, IOM DTM and 158 more. No single outlet is above 5% of the sample. **77 of the 260
carry a casualty count and 44 carry a displacement figure**, because an event without a number
attached is just a claim.

**32 named conflicts** appear in that sample alone, from Russia–Ukraine, US–Iran, Israel–Hamas and
the Red Sea Crisis through Sudan, Myanmar, Haiti, Somalia, the M23 rebellion, the Korean peninsula
and China–Taiwan. Coverage runs continuously from **March 2026 to today**.

### How it is built

> **Every event is its own server-rendered page.** 6,983 of them, each with a canonical URL, so a
> single event can be linked, shared and indexed on its own rather than living only inside a
> JavaScript map. Query parameters are stripped to a whitelist so tracking junk cannot mint
> duplicates.
>
> **Naval OSINT as a first-class theatre.** A dedicated Strait Tracker follows chokepoint traffic
> and incidents — Hormuz, the Red Sea — with its own worker, its own mobile build and a separate
> news pipeline.
>
> **Autonomous posting.** Significant events are published to Bluesky over AT Protocol without a
> human in the loop.
>
> **Edge-native.** Cloudflare Workers and D1, which is what makes a free, global, no-account map
> financially possible for one person to run.
>
> **Deliberately open to machines.** `robots.txt` explicitly welcomes GPTBot, PerplexityBot,
> ClaudeBot and every social crawler. The data is meant to be reachable, not fenced.

`conflict data` · `naval OSINT` · `live map` · `verified events, not headlines` · `6,983 events` · `Cloudflare Workers` · `AT Protocol` · `MIT`

---

## <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/ka-tet-dark.svg"><img src="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/ka-tet-light.svg" alt="" width="22" height="22" align="top"></picture> Featured work

> ### [**ka-tet**](https://github.com/indicaindependent/ka-tet) · orchestral agentic AI
> Four AI agents and one human, bound to one task. The architecture everything else on this
> account is now built with — a fellowship with a shared purpose, not a prompt chain.
>
> <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/charts/ka-tet-roster.svg"><img src="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/charts/ka-tet-roster.svg" alt="The ka-tet roster: four agent seats and the human dinh at the centre." width="100%"></picture>

> ### [**VoxTerrae**](https://voxterrae.app) · the door from the map to the room
> *Vox terrae* — voice of the earth. A WarHeatMap-branded IRC client (Python / PySide6, MIT) that
> puts a real conversation next to the live map. Dual-network, portable Windows build, no account
> required.
>
> [voxterrae.app](https://voxterrae.app) · [source](https://github.com/indicaindependent/voxterrae) · MIT

> ### [**AXIOM**](https://github.com/indicaindependent/axiom) · autonomous community security
> Four independent workers that moderate a live community and publish the method they use, so an
> owner can audit the reasoning instead of trusting a black box.

---

## <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/bolt-dark.svg"><img src="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/bolt-light.svg" alt="" width="22" height="22" align="top"></picture> Also running

**[Tuck](https://tuck.osintnet.uk)** — free financial intelligence. Congressional trades and
disclosure data, handed back. *"What Wall Street hoards, we hand back"* is Tuck's line, and it is
the whole account's thesis. · [source](https://github.com/indicaindependent/tuck)

**[Kelvin](https://github.com/indicaindependent/kelvin)** — quant trading performance and risk
observability. Absolute zero, absolute discipline. The discipline is published; the calibration is not.

**[VibeMaestro](https://vibemaestro.app)** — one conductor for a whole ecosystem of AI-native
apps. Open source. · [source](https://github.com/indicaindependent/vibemaestro)

---

## <picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/shield-dark.svg"><img src="https://raw.githubusercontent.com/indicaindependent/indicaindependent/main/assets/icons/shield-light.svg" alt="" width="22" height="22" align="top"></picture> The two hubs

Everything else lives in one of these, and each repo is still public on its own.

> ### [**VPDLNY tools**](https://github.com/indicaindependent/vpdlny-tools)
> The Vulnerable Defense League of NY mission: free tools for defending people who cannot buy
> the software that would help them. Crisis routing, consumer safety, accessibility, and the
> small business work. **The tooling is public even where the work is not.**

> ### [**IIM hub**](https://github.com/indicaindependent/iim-hub)
> Indica Independent Media: open intelligence, built in the open. The Bluesky and AT Protocol
> estate, the OSINT worker patterns, the agent seats, and the research studies — indexed in
> one place instead of scattered across this page.

---

<div align="center">

`100% Creative Clarity` · [osintnet.uk](https://osintnet.uk) · [Bluesky](https://bsky.app/profile/indica.osintnet.uk) · [Support the mission](https://donate.skygive.app)

</div>
