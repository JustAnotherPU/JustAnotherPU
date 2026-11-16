### Hi, I'm JustAnotherPU

I build software for cars, homes and networks that their vendors never meant to open up.

#### What I work on

- Apps for the BMW iDrive 7 (MGU) head unit, found by reverse engineering it: a video client, game streaming over 5G, home cameras on the car screen, Waze arrows on the head-up display. Most of them install through the community [MGU Store](https://github.com/robertnisipeanu/mgu-store), which I also contribute to.
- Solar and home automation on Home Assistant. The commercial PV forecasts were off for my roof, so I wrote my own, and I run appliances locally with their vendor cloud cut off.
- Networking and self-hosting: Proxmox, UniFi, WireGuard, Tailscale.
- LLMs running on local GPUs (llama.cpp, Qwen) as a voice assistant for Home Assistant.

#### Selected projects

| Project | What it does |
| --- | --- |
| [ridetube](https://github.com/JustAnotherPU/ridetube) | Unofficial video client for the BMW iDrive 7, with SponsorBlock |
| [roofcast](https://github.com/JustAnotherPU/roofcast) | Self-calibrating multi-model PV forecast for Home Assistant, Solcast-compatible output for EMHASS |
| [waze-hud](https://github.com/JustAnotherPU/waze-hud) | Waze turn-by-turn arrows on the BMW head-up display and instrument cluster |
| [moonride](https://github.com/JustAnotherPU/moonride) | Moonlight game streaming on the iDrive 7 screen, with car audio and 5G play over Tailscale |
| [mgu-apps](https://github.com/JustAnotherPU/mgu-apps) | iDrive 7 apps and tools: iDrive Monitor, Tailscale, Node.js 22 |
| [hisense-local](https://github.com/JustAnotherPU/hisense-local) | Home Assistant add-on that runs a Hisense washer locally, vendor cloud cut off |

#### Merged upstream

[EMHASS](https://github.com/davidusb-geek/emhass/pull/1344) (custom PV forecast recipe), [MGU Store](https://github.com/robertnisipeanu/mgu-store/pulls?q=author%3AJustAnotherPU) (render and Wi-Fi uplink fixes), [OBDb BMW X5](https://github.com/OBDb/BMW-X5/pull/223) (validated DME PIDs), [car-apps](https://github.com/IterioDev/car-apps/pull/14) (Tailscale SOCKS5 proxy).
