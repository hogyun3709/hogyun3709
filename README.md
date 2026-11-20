## Hogyun Kim

Full-stack engineer based in South Korea (UTC+9), about four years in. I build and run production systems where money and devices meet software: payment gateways, a vendor POS, card terminals, kiosks and the APIs behind them. I lead a two-person development team at ETRAN CNC. Before that, I worked fully remotely in English on a multinational Flutter team.

Most of my work lives in private client and company repositories, so the contribution graph shows the activity but not the code. I'm glad to walk through the architecture and the decisions behind it.

**Stack:** TypeScript · NestJS · Next.js · React · Prisma · Node.js · Python (FastAPI) · PostgreSQL · MySQL/MariaDB · Redis · AWS · Docker · Flutter

### Selected work

- **Theme park commerce platform.** Sole engineer for the customer site, HQ admin, merchant and partner portals, Windows kiosks and a shared NestJS API (214 Prisma models) covering tickets, ryokan stays, memberships and merchant sales. It integrates NicePay (cards, KakaoPay, Naver Pay), a vendor POS and card terminals, and revenue is reconciled against the payment gateway's raw approval data rather than our own labels. [nijimori.kr](https://www.nijimori.kr)
- **Tiki Takgu.** A table-tennis lesson, venue and league product I build and operate on my own: a NestJS API, two Next.js admin apps and a Flutter app on the [App Store](https://apps.apple.com/kr/app/%ED%8B%B0%ED%82%A4%ED%83%81%EA%B5%AC/id6757993234) and [Google Play](https://play.google.com/store/apps/details?id=com.tikitakgu). [tikitakgu.com](https://tikitakgu.com)
- **Data and infrastructure.** Moved a cinema booking platform to a new AWS account with verified row counts and a 30-day fallback, and cut a campaign dashboard query from 41 s to 544 ms while keeping the order users saw.
- **Upstream fix in Kakao's Flutter SDK.** Reported a Flutter Web failure in scope-based Kakao login (KOE006). Kakao confirmed a missing web-only parameter and shipped the fix in v1.4.3 (May 2023). [Report](https://devtalk.kakao.com/t/flutter-web-koe006-redirect-uri/129291) · [Changelog](https://pub.dev/packages/kakao_flutter_sdk/changelog#143)

### How I work

I use AI coding agents (Claude Code, Codex) every day for implementation. My own time goes into the judgment around it: which problem is real, what must stay correct, which trade-off to accept, and how to prove the result with tests, measurements and reconciliation.

### Contact

[LinkedIn](https://www.linkedin.com/in/hogyun-kim-02b29110b) · [tikitakgu.com](https://tikitakgu.com) · hogyun3709@gmail.com
