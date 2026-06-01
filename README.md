<div align="center">
  <img src="./assets/banner.svg" alt="Baalvion Industries Private Limited" width="100%" />
</div>

<div align="center">

<br/>

**Building next-generation global B2B trade infrastructure**

AI-driven vendor intelligence&nbsp; &middot; &nbsp;Trade-finance APIs&nbsp; &middot; &nbsp;Compliance automation

<br/>

[![Website](https://img.shields.io/badge/baalvion.com-0A0E27?style=for-the-badge&logo=googlechrome&logoColor=5B8CFF)](https://baalvion.com)
[![Group](https://img.shields.io/badge/Baalvion_Group-10183C?style=for-the-badge&logo=safari&logoColor=36E0C4)](https://baalviongroup.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/baalvion)
[![X](https://img.shields.io/badge/Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/baalvion)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@baalvion)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@baalvion)

![Location](https://img.shields.io/badge/Headquarters-India-1E1147?style=flat-square)
![CIN](https://img.shields.io/badge/CIN-U43121OD2025PTC048479-1E1147?style=flat-square)
![Status](https://img.shields.io/badge/Status-Actively_building-36E0C4?style=flat-square)

</div>

---

## 🌐 Who we are

**Baalvion Industries Private Limited** is a technology group engineering the digital backbone of
global commerce. We design, build, and operate an integrated platform that connects **buyers,
suppliers, financiers, and regulators** across borders — turning fragmented, paperwork-heavy trade
into a single programmable, compliant, and intelligent system.

From **trade execution and finance** to **vendor intelligence, compliance automation, and
infrastructure-as-a-service**, our products share one mission: *make global B2B trade fast,
trustworthy, and accessible to everyone.*

> One identity. One platform. Every market.

---

## 🚀 Platforms &amp; Products

### Flagship platforms

| Platform | What it does | Live |
| :--- | :--- | :--- |
| 🏛️ **Baalvion Group** | Corporate group &amp; holding company | [baalviongroup.com](https://baalviongroup.com) |
| 🌍 **Global Trade OS** | Cross-border trade execution, finance, compliance &amp; logistics | [market.baalvion.com](https://market.baalvion.com) |
| 🛰️ **BaalvionStack** | Enterprise proxy &amp; data network — secure access at scale | [baalvionstack.com](https://baalvionstack.com) |
| 🔐 **Proxy by BaalvionStack** | Self-serve proxy &amp; data-network console | [proxy.baalvionstack.com](https://proxy.baalvionstack.com) |

### Marketplaces &amp; verticals

| Product | What it does | Live |
| :--- | :--- | :--- |
| 🎯 **ControlTheMarket** | Competitive talent challenges &amp; skill-assessment marketplace | [controlthemarket.com](https://controlthemarket.com) |
| 📈 **MarketUnderworld** | Market-intelligence &amp; trading platform | [marketunderworld.com](https://marketunderworld.com) |
| 📚 **Imperialpedia** | Collaborative knowledge &amp; reference encyclopedia | [imperialpedia.com](https://imperialpedia.com) |
| 💎 **Amarise Maison Avenue** | Luxury house — digital storefront &amp; brand experience | [amarisemaisonavenue.com](https://amarisemaisonavenue.com) |
| ⚖️ **Law Elite Network** | Premium legal network &amp; advisory platform | [lawelitenetwork.com](https://lawelitenetwork.com) |
| ⛏️ **Baalvion Mining** | Minerals &amp; resources division | [mining.baalvion.com](https://mining.baalvion.com) |
| 🛍️ **BaalvionStack Shop** | Plans, add-ons &amp; commerce | [shop.baalvionstack.com](https://shop.baalvionstack.com) |

### Corporate &amp; operations surfaces

| Surface | Purpose | Live |
| :--- | :--- | :--- |
| 🏢 **About Baalvion** | Vision, businesses &amp; leadership | [about.baalvion.com](https://about.baalvion.com) |
| 📊 **Investor Relations** | Press releases, news &amp; investor communications | [ir.baalvion.com](https://ir.baalvion.com) |
| 🧭 **Unified Dashboard** | Cross-business operations, HR &amp; analytics console | [dashboard.baalvion.com](https://dashboard.baalvion.com) |
| 🤝 **Baalvion Connect** | Brand &amp; partner engagement | [connect.baalvion.com](https://connect.baalvion.com) |
| 💼 **Careers** | Open roles across the group | [jobs.baalvion.com](https://jobs.baalvion.com) |

---

## 🏗️ Platform architecture

Our entire ecosystem runs on a single, governed **platform foundation** — a federated monorepo
organized around bounded contexts, with shared infrastructure and one centralized identity plane.

```
                         ┌──────────────────────────────┐
                         │   Centralized Identity (SSO)  │
                         │   RS256 · OAuth2 · RBAC/ABAC  │
                         └───────────────┬──────────────┘
                                         │
            ┌────────────────────────────┼────────────────────────────┐
            │                 API Gateway / BFF Federation             │
            └───┬───────────┬───────────┬───────────┬───────────┬──────┘
                │           │           │           │           │
            ┌───┴───┐  ┌────┴───┐  ┌────┴───┐  ┌────┴────┐  ┌───┴────┐
            │Identity│  │Commerce│  │ Trade  │  │Knowledge│  │ Infra  │
            │ domain │  │ domain │  │/Finance│  │ domain  │  │ domain │
            └────────┘  └────────┘  └────────┘  └─────────┘  └────────┘
              60+ domain microservices · event-driven (Redis Streams) · multi-tenant (Postgres RLS)
```

- **Centralized auth** — one RS256 issuer, no hand-rolled JWT, SSO across every property
- **Federated gateway** — a single edge fronting independent domain services
- **Multi-tenancy** — Postgres Row-Level Security with fail-closed tenant isolation
- **Hybrid RBAC + ABAC** — platform → country → organization authorization hierarchy
- **Event-driven** — durable Redis Streams event bus with tamper-evident audit trails
- **Polyglot by design** — TypeScript/Node for platform &amp; product, Java/Spring Boot for financial-grade services

---

## 🛠️ Technology

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)

</div>

---

## 📊 By the numbers

<div align="center">

| | | |
| :---: | :---: | :---: |
| **6** | **60+** | **17** |
| bounded-context domains | domain microservices | live web properties |
| **Polyglot** | **Multi-tenant** | **Centralized** |
| Node &amp; Java/Spring | Postgres RLS isolation | RS256 single sign-on |

</div>

---

## 🤝 Work with us

- 🧑‍💼 **Careers** — we're hiring across engineering, trade, and operations → [jobs.baalvion.com](https://jobs.baalvion.com)
- 📈 **Investors** — financial news &amp; communications → [ir.baalvion.com](https://ir.baalvion.com)
- 🤝 **Partnerships** — integrate or co-build with us → [connect.baalvion.com](https://connect.baalvion.com)
- ✉️ **Contact** — [infra.baalvion@gmail.com](mailto:infra.baalvion@gmail.com)

---

<div align="center">

<sub>© 2025–2026 <b>Baalvion Industries Private Limited</b> &middot; CIN U43121OD2025PTC048479 &middot; India</sub><br/>
<sub>Source published for transparency. All rights reserved unless a repository states otherwise.</sub>

</div>
