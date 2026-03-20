# OpenWrt Enhanced

A fork of OpenWrt with improved MT76 Wi-Fi driver support.

## What's different

- **Antenna chain count** — antenna chain count support via DTS
- **TX power correction** — EEPROM power offset correction
- **Advanced Wi-Fi controls** — 21 new knobs exposed via LuCI
- **Rate control** — runtime tuning of MCS floor, retry count, aggregation support
- **RF & CCA** — manual sensitivity thresholds with SCS auto-adjust support
- **Forced rate control** — force MCS, NSS and bandwidth support
- **Regulatory bypass** — bypassed power limits for RS and PA
- **Bufferbloat** — Smart Queue Management support
- **Encrypted DNS** — HTTPS DNS proxy with HTTP/3 support
- **Google BBR** — Google BBR TCP congestion support
- **irqbalance** — CPU interrupt distribution

## Supported hardware

| Device | Target | Wi-Fi |
|--------|--------|------|
| Netgear R6800 | ramips/mt7621 | MT7615N |

## Build

Firmware is built automatically via GitHub Actions on every push.
Download the latest build from the [Actions tab](https://github.com/openwrt-enhanced/openwrt/actions).

## Repositories

- [openwrt](https://github.com/openwrt-enhanced/openwrt) — Main OpenWrt fork
- [mt76](https://github.com/openwrt-enhanced/mt76) — MT76 driver fork
- [luci](https://github.com/openwrt-enhanced/luci) — LuCI fork

## Status

Work in progress — tested on Netgear R6800 only.
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
