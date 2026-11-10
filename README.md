### Founder of [LatentEdge](https://latentedge.io) - AI products, automation, and full-stack engineering for web and iOS.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white)
![D1](https://img.shields.io/badge/D1_SQLite-003B57?logo=sqlite&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?logo=swift&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

## Portfolio

| Live | Beta | Alpha | In development | iOS apps | Shared packages |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **35** | **11** | **27** | **43** | **15** | **16** |

## Delivery pipeline

AI agents run each roadmap item through spec, build, test, and deploy, with human review at the gates that matter.

```mermaid
flowchart LR
  A[Roadmap item] --> B[Spec]
  B --> C{Review gate}
  C --> D[Agent build]
  D --> E[CI tests]
  E --> F[Deploy to Cloudflare]
  F --> G[Metrics and feedback]
  G --> A
```

## Platform

Every app starts on the same stack and the same in-house packages.

```mermaid
flowchart TB
  Web[Next.js static site<br/>Cloudflare Pages] --> API[Cloudflare Worker API]
  iOS[SwiftUI iOS app] --> API
  API --> DB[(D1 SQLite)]
  API --> Pkg[Shared packages<br/>auth · OTP · email · forms · IAP · telemetry · roles]
```

## Selected products

| Product | Category | Platform |
|---|---|---|
| [Write My Card AI](https://writemycardai.com) | AI writing | Web |
| [Brain Dump](https://braindump.latentedge.io) | Voice-first productivity | Web |
| [The Grateful List](https://thegratefullist.com) | Wellness | Web, iOS |
| [Cernita](https://cernita.latentedge.io) | Photo management | Web, iOS |
| [SkatePhone](https://skatephone.com) | Sports | Web, iOS |
| [Lost Pet Radar](https://lostpetradar.com) | Community alerts | Web |
| [Life Lore](https://lifelore.latentedge.io) | Personal writing | Web |
| [Vibe Helping](https://vibehelping.com) | Website review tool | Web |
| [Feedback](https://feedback.latentedge.io) | Feedback widget | Web |

## Open source

| Repository | Description |
|---|---|
| [status-page](https://github.com/LatentFreedom/status-page) | Self-hosted status page: Next.js, Worker, and D1 from one config file |
| [hometodo](https://github.com/LatentFreedom/hometodo) | Self-hosted tracker for home and life tasks |
| [appstore-notifications-package](https://github.com/LatentFreedom/latentedge-appstore-notifications-package) | App Store Server Notifications V2 for Cloudflare Workers |
| [cloudflare_bulk_dns_updater](https://github.com/LatentFreedom/cloudflare_bulk_dns_updater) | Bulk-update A records across Cloudflare zones |

**Contact:** [nic@latentedge.io](mailto:nic@latentedge.io) · [latentedge.io](https://latentedge.io)
