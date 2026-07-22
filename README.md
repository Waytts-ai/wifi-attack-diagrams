# WiFi attack diagrams

68 original, plain-language diagrams explaining how WiFi attacks work
and how they are detected — ARP spoofing, evil-twin access points, rogue DHCP
servers, DNS hijacking, deauthentication floods, IPv6 router spoofing and more.

**Licence: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).** Use them in
talks, courses, blog posts, documentation — commercially or not. The only
requirement is credit.

## Credit line

```
Diagram by WifiThreatWatch — CC BY 4.0
https://wifithreatwatch.com/diagrams
```

## Index

| Diagram | What it shows | Full explanation |
| --- | --- | --- |
| [`always-on.png`](images/always-on.png) | the app watches while your PC is on — the Nano never blinks, so the 3 a.m. attack is still caught | [read](https://wifithreatwatch.com/nano) |
| [`arp-cache-vs-wire.png`](images/arp-cache-vs-wire.png) | reading the table can't witness the poisoning happen; sniffing the wire can | [read](https://wifithreatwatch.com/threats/arp-spoofing) |
| [`baseline-vs-stranger.png`](images/baseline-vs-stranger.png) | four devices you authorized — and one you didn't | [read](https://wifithreatwatch.com/guides/what-are-rogue-devices) |
| [`bssid-roster.png`](images/bssid-roster.png) | two access points broadcasting one SSID — only one is your real router | [read](https://wifithreatwatch.com/guides/how-to-detect-an-evil-twin) |
| [`coffee-shop-threat.png`](images/coffee-shop-threat.png) | a stranger nearby broadcasts a friendly network name and waits — WifiThreatWatch stands in the middle, warns you in plain English, and cuts him off | [read](https://wifithreatwatch.com) |
| [`corroboration.png`](images/corroboration.png) | every extra reporter raises one shared count — it never multiplies the warnings on your screen | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`coverage-diagram.png`](images/coverage-diagram.png) | a VPN encrypts the line; WifiThreatWatch watches the room the attacker is standing in | [read](https://wifithreatwatch.com/compare) |
| [`deauth-flood.png`](images/deauth-flood.png) | the AP is still right there — but you keep getting kicked off | [read](https://wifithreatwatch.com/threats/deauth-flood) |
| [`deauth-to-twin.png`](images/deauth-to-twin.png) | denial of service is rarely the point — it’s the setup for the twin | [read](https://wifithreatwatch.com/guides/how-to-detect-a-deauth-attack) |
| [`dedup-alert.png`](images/dedup-alert.png) | an evil twin and a gateway ARP spoof are often one attack — we de-duplicate them so you act once | [read](https://wifithreatwatch.com/threats/evil-twin) |
| [`defense-layers.png`](images/defense-layers.png) | awareness is the first line — if you connect to the impostor anyway, two more layers are waiting | [read](https://wifithreatwatch.com/threats/homoglyph-ssid) |
| [`den-arp-flip.png`](images/den-arp-flip.png) | airline-lounge net — one IP’s hardware address kept flipping (~37 devices present) | [read](https://wifithreatwatch.com/blog/denver-airport-wifi-security-scan) |
| [`den-open-networks.png`](images/den-open-networks.png) | every airport network the scan saw was open — no WiFi-layer encryption | [read](https://wifithreatwatch.com/blog/denver-airport-wifi-security-scan) |
| [`den-ssid-roster.png`](images/den-ssid-roster.png) | 73 access points, one network name — 52 recognized, 18 suspicious BSSID, 3 evil-twin-nearby | [read](https://wifithreatwatch.com/blog/denver-airport-wifi-security-scan) |
| [`detection-ladder.png`](images/detection-ladder.png) | a snapshot sees one moment; a watch sees the moment it joins | [read](https://wifithreatwatch.com/guides/what-are-rogue-devices) |
| [`device-vs-network.png`](images/device-vs-network.png) | the app guards the machine it runs on — the Nano watches everything on the WiFi, installed or not | [read](https://wifithreatwatch.com/nano) |
| [`dhcp-watch.png`](images/dhcp-watch.png) | every OFFER and ACK checked against the one legitimate server — a stranger stands out | [read](https://wifithreatwatch.com/guides/how-to-detect-a-rogue-dhcp-server) |
| [`dns-baseline-check.png`](images/dns-baseline-check.png) | a resolver you didn’t set, on a network you didn’t change — that’s the anomaly | [read](https://wifithreatwatch.com/guides/how-to-detect-dns-hijacking) |
| [`dns-canary.png`](images/dns-canary.png) | the resolver IP looks the same — the answer is what gives it away | [read](https://wifithreatwatch.com/threats/dns-spoofing) |
| [`dns-redirect.png`](images/dns-redirect.png) | the same lookup, answered by whichever resolver sits in the middle | [read](https://wifithreatwatch.com/threats/dns-anomaly) |
| [`dns-signal.png`](images/dns-signal.png) | a resolver change we caused ourselves is not an attack | [read](https://wifithreatwatch.com/threats/dns-anomaly) |
| [`escalation.png`](images/escalation.png) | a new device is informational — until it acts like an attacker, and the same detection turns critical | [read](https://wifithreatwatch.com/threats/rogue-device) |
| [`evil-twin-lure.png`](images/evil-twin-lure.png) | same SSID, stronger signal — the device prefers the attacker's access point | [read](https://wifithreatwatch.com/threats/evil-twin) |
| [`foothold-spread.png`](images/foothold-spread.png) | a hostile device quietly maps the network and reads what flows past | [read](https://wifithreatwatch.com/guides/what-are-rogue-devices) |
| [`freeloader-vs-attacker.png`](images/freeloader-vs-attacker.png) | a device list shows the row — not which one it is | [read](https://wifithreatwatch.com/guides/is-someone-on-my-wifi-windows) |
| [`gateway-bypass.png`](images/gateway-bypass.png) | the attacker made itself your gateway and DNS — so all it gets to forward is ciphertext it can’t read | [read](https://wifithreatwatch.com/threats/rogue-dhcp) |
| [`howitworks-arp-detour.png`](images/howitworks-arp-detour.png) | the route you assume vs. the one you get — every packet detours through the attacker first | [read](https://wifithreatwatch.com/how-it-works) |
| [`howitworks-identity-reset.png`](images/howitworks-identity-reset.png) | the adapter rolls a fresh MAC and pulls a new DHCP lease — the address the attacker was poisoning no longer exists | [read](https://wifithreatwatch.com/how-it-works) |
| [`invisible-chars.png`](images/invisible-chars.png) | some look-alike tricks use characters that render as nothing at all | [read](https://wifithreatwatch.com/guides/how-to-spot-a-fake-wifi-name) |
| [`live-recheck.png`](images/live-recheck.png) | flagged after you already joined? you’re warned in the app on the next re-check, not at your next scan | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`lockdown-sequence.png`](images/lockdown-sequence.png) | a few minutes turns an open door into a closed one | [read](https://wifithreatwatch.com/guides/is-someone-on-my-wifi-windows) |
| [`mesh-nodes.png`](images/mesh-nodes.png) | every node broadcasting your network name — signal, load, and trust at a glance | [read](https://wifithreatwatch.com) |
| [`mesh-vs-twin.png`](images/mesh-vs-twin.png) | your mesh uses many radios on purpose — the trick is flagging only the one that doesn’t belong | [read](https://wifithreatwatch.com/guides/how-to-detect-an-evil-twin) |
| [`mitm-path.png`](images/mitm-path.png) | the same connection, re-routed so your traffic passes through the adversary | [read](https://wifithreatwatch.com/threats/man-in-the-middle) |
| [`monitor-mode.png`](images/monitor-mode.png) | Windows can only infer an attack from its symptoms — a monitor radio reads the attack frames themselves | [read](https://wifithreatwatch.com/nano) |
| [`nano-device.png`](images/nano-device.png) | a small always-on sentry you plug into any Wi-Fi — two radios, no screen, never off | [read](https://wifithreatwatch.com/nano) |
| [`nano-handoff.png`](images/nano-handoff.png) | the moment you connect, the app finds the Nano and reads what it has already seen — before you trust the network | [read](https://wifithreatwatch.com/nano) |
| [`nano-sensor.png`](images/nano-sensor.png) | a headless sensor running the same detectors 24/7 — even when your PC is asleep | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`network-effect.png`](images/network-effect.png) | the database is young — every device that joins makes the next warning likelier to already be there | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`network-reputation.png`](images/network-reputation.png) | every nearby network checked against the shared database — before you tap connect | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`nslookup-check.png`](images/nslookup-check.png) | resolve a name whose correct IP you already know — the answer is what gives it away | [read](https://wifithreatwatch.com/guides/how-to-detect-dns-spoofing) |
| [`on-device-hash.png`](images/on-device-hash.png) | the attack is documented so the next device recognizes it — your browsing, files, exact location and identity stay out of it | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`ordered-pipeline.png`](images/ordered-pipeline.png) | six stages in one fixed order — the encrypted tunnel comes up last, not first | [read](https://wifithreatwatch.com/how-it-works) |
| [`path-vs-contents.png`](images/path-vs-contents.png) | a VPN hides what you send — not the fact that an attacker is on your path | [read](https://wifithreatwatch.com/guides/how-to-detect-a-man-in-the-middle-attack) |
| [`pns-arp-blip.png`](images/pns-arp-blip.png) | two brief blips, both randomized (LAA) MACs — consistent with MAC rotation, not a sustained attack | [read](https://wifithreatwatch.com/blog/pensacola-airport-wifi-security-scan) |
| [`pns-crowd.png`](images/pns-crowd.png) | 85 devices new to this laptop — everyone else in the terminal on the same open network, not 85 attackers | [read](https://wifithreatwatch.com/blog/pensacola-airport-wifi-security-scan) |
| [`pns-quad9.png`](images/pns-quad9.png) | PNS ran on Quad9 (9.9.9.9), which blocks known-malicious domains — a security-conscious choice | [read](https://wifithreatwatch.com/blog/pensacola-airport-wifi-security-scan) |
| [`reclaim-loop.png`](images/reclaim-loop.png) | if the attacker re-poisons, we change identity again — up to five times — until the lock breaks | [read](https://wifithreatwatch.com/threats/arp-spoofing) |
| [`reconnect-guard.png`](images/reconnect-guard.png) | we can’t stop the radio frames — but we name the attack and treat the network offering you back as suspect | [read](https://wifithreatwatch.com/threats/deauth-flood) |
| [`retry-loop.png`](images/retry-loop.png) | a new identity every attempt — up to five — until one beats the re-poison | [read](https://wifithreatwatch.com/how-it-works) |
| [`rogue-categories.png`](images/rogue-categories.png) | one label, four very different things | [read](https://wifithreatwatch.com/guides/what-are-rogue-devices) |
| [`rogue-dhcp.png`](images/rogue-dhcp.png) | one broadcast, two answers — a second server volunteers as your gateway | [read](https://wifithreatwatch.com/threats/rogue-dhcp) |
| [`rogue-roster.png`](images/rogue-roster.png) | a MAC the baseline has never seen is surfaced as new | [read](https://wifithreatwatch.com/threats/rogue-device) |
| [`rogue-sweep.png`](images/rogue-sweep.png) | every host pinged at once — one MAC answers that shouldn't | [read](https://wifithreatwatch.com/threats/rogue-device) |
| [`router-device-list.png`](images/router-device-list.png) | every device accounted for — except one you didn't invite | [read](https://wifithreatwatch.com/guides/is-someone-on-my-wifi-windows) |
| [`shared-signal-flow.png`](images/shared-signal-flow.png) | one attack caught, reported, and turned into an early warning for the next person | [read](https://wifithreatwatch.com/mission) |
| [`ssid-canon.png`](images/ssid-canon.png) | different bytes that reduce to the same key are the tell | [read](https://wifithreatwatch.com/threats/homoglyph-ssid) |
| [`ssid-diff.png`](images/ssid-diff.png) | same pixels, different bytes — one letter isn't Latin | [read](https://wifithreatwatch.com/threats/homoglyph-ssid) |
| [`symptom-checklist.png`](images/symptom-checklist.png) | none prove it alone — together, worth two minutes | [read](https://wifithreatwatch.com/guides/is-someone-on-my-wifi-windows) |
| [`threat-report.png`](images/threat-report.png) | a confirmed attack names the threat in full — and is never tied to you | [read](https://wifithreatwatch.com) |
| [`threats-arp-detour.png`](images/threats-arp-detour.png) | every packet detours through the attacker before reaching your router | [read](https://wifithreatwatch.com/threats/arp-spoofing) |
| [`threats-identity-reset.png`](images/threats-identity-reset.png) | a fresh MAC and IP break the attacker's lock before the tunnel comes up | [read](https://wifithreatwatch.com/threats/man-in-the-middle) |
| [`tunnel-answer.png`](images/tunnel-answer.png) | the same canary that came back tampered on the local network resolves correctly through Active Defense | [read](https://wifithreatwatch.com/threats/dns-spoofing) |
| [`tunnel-resolver.png`](images/tunnel-resolver.png) | your lookups ride the encrypted tunnel to a resolver we control — the swapped local one never sees them | [read](https://wifithreatwatch.com/threats/dns-anomaly) |
| [`twin-baseline.png`](images/twin-baseline.png) | the current association weighed against the saved BSSID, gateway MAC and DNS | [read](https://wifithreatwatch.com/threats/evil-twin) |
| [`two-channels.png`](images/two-channels.png) | the cloud database answers questions your device asks · the Nano announces itself only on your own WiFi | [read](https://wifithreatwatch.com/shared-intelligence) |
| [`two-signal-gate.png`](images/two-signal-gate.png) | both signals must agree before we interrupt you — a stale cache entry alone stays quiet | [read](https://wifithreatwatch.com/how-it-works) |
| [`warning-journey.png`](images/warning-journey.png) | a detection climbs into one shared row; the next device finds it only when it asks — devices never message each other | [read](https://wifithreatwatch.com/shared-intelligence) |

## Where these come from

They were drawn for [WifiThreatWatch](https://wifithreatwatch.com), a Windows
network-security app that detects WiFi attacks on the local network. Each
diagram links to the write-up it illustrates.

Browse them rendered, with animation: https://wifithreatwatch.com/diagrams

## How to push this repo

```sh
cd github-repo
git init && git add -A
git commit -m "WiFi attack diagrams, CC BY 4.0"
gh repo create wifi-attack-diagrams --public --source=. --push
```

Then add the repo URL to `sameAs` in the site's `index.html`.
