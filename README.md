<div align="center">

# 🐳 ROASEQ

**The open-source attribution platform for ecommerce.**
**Your events. Your models. Your database.**

[⭐ Star on GitHub](https://github.com/juansbiz/roaseq) &nbsp;·&nbsp; [📖 Docs](https://github.com/juansbiz/roaseq#quick-start) &nbsp;·&nbsp; [🐛 Open an issue](https://github.com/juansbiz/roaseq/issues) &nbsp;·&nbsp; [🐦 @juansbizz](https://twitter.com/juansbizz)

</div>

---

## The pitch

**ROASEQ is the FOSS alternative to Triple Whale.**

Multi-touch attribution. Channel ROI. Journey stitching. Every ad click, every checkout, every email open, every repeat purchase: a row in your own Postgres. Free. Self-hostable. Yours forever.

---

## The problem

Triple Whale, Northbeam, Polar, Rockerbox, Wicked Reports. They all do the same thing. They hold your attribution data in their warehouse, charge you a flat fee (or worse) to see it, and lock you into a 12-month contract.

A 2025 audit by Wicked Reports and Tier 11 across 2,000+ brands found third-party attribution tools misreport up to 30% of revenue. Bottom-funnel channels get over-credited. Prospecting looks broken even when it's working. Brands scale the wrong campaigns and kill the ones actually creating customers.

None of them are open source. None of them self-host. None of them put the events in your database where you can run your own models.

ROASEQ does.

---

## What you get

🧠 **Multi-touch attribution.** First-touch, last-touch, linear, time-decay, position-based, data-driven. Pick the model that fits your business, or build your own.

💵 **No percentage of ad spend. No annual contract.** Free, self-hosted. Or flat-rate cloud. Forever.

🔓 **The events are yours.** Every ad click, every checkout, every email open, every repeat purchase: a row in your own Postgres. Export anytime. Run any model you want.

---

## What you replace

| Closed source | What it charges | ROASEQ |
|---|---|---|
| **Triple Whale** | $179 to $749/mo, enterprise custom, 12-month lock-in | Free self-host, or flat cloud |
| **Northbeam** | $1,500/mo starter, custom above that, demo-gated | Free self-host, or flat cloud |
| **Polar Analytics** | Quote-based, "Core" bundle discount, your own Snowflake (but theirs) | Free self-host, YOUR Postgres |
| **Rockerbox** | No public pricing, $250K+ media spend to qualify | Free self-host, no qualification |
| **Wicked Reports** | $499 to $999/mo, $4,999/mo enterprise | Free self-host, or flat cloud |

The same answers to "which ad is profitable" and "where did this customer come from," in your own database, without the vendor markup.

---

## Quick start

Self-host with Docker:

```bash
git clone https://github.com/juansbiz/roaseq.git
cd roaseq
cd docker && docker compose up
```

Or run the dev stack:

```bash
git clone https://github.com/juansbiz/roaseq.git
cd roaseq
npm install
npm run dev
```

That's it. Open the dashboard, connect your store, connect your ad accounts, and the events start flowing.

---

## Why FOSS

Because attribution data should not be a hostage. Because "where's my money going" is the most important question in ecommerce, and you should not have to pay rent to ask it. Because closed-source SaaS had its time.

We are building the open-source ecommerce infrastructure layer. Attribution is the first piece.

---

<sub>Your events. Your models. Your database. Open source, forever.</sub>
