<div align="center">

<picture>
  <!-- Dark mode (use WHITE logo) -->
  <source 
    media="(prefers-color-scheme: dark)" 
    srcset="https://github.com/user-attachments/assets/62a7a672-a84a-437c-b5aa-fa83d6a0091e" 
  />

  <!-- Light mode (use DARK logo) -->
  <source 
    media="(prefers-color-scheme: light)" 
    srcset="https://github.com/user-attachments/assets/059b109e-5fdc-47ad-bb42-ee483d7128e3" 
  />

  <!-- Fallback (usually light version) -->
  <img 
    width="128" 
    height="128" 
    alt="ValueGuardAI" 
    src="https://github.com/user-attachments/assets/059b109e-5fdc-47ad-bb42-ee483d7128e3" 
  />
</picture>
<br/>
<br/>

# ValueGuardAI

### The AI-Powered Brand Protection Operating System

**Detect · Enforce · Protect**

We build intelligent infrastructure that safeguards brands from counterfeits, unauthorized sellers, and intellectual property infringement — across every marketplace, platform, and geography on earth.

<br/>

[![Website](https://img.shields.io/badge/Website-valueguard.ai-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://valueguard.ai)
[![Documentation](https://img.shields.io/badge/Docs-docs.valueguard.ai-000000?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.valueguard.ai)
[![Blog](https://img.shields.io/badge/Blog-Research%20%26%20Insights-FF6B35?style=for-the-badge&logo=hashnode&logoColor=white)](https://valueguard.ai/blog)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ValueGuardAI-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/valueguardai)

</div>

<br/>

---

<br/>

## 🏢 About Us

ValueGuardAI is building the next-generation operating system for brand protection. Global counterfeiting is a **$2.3 trillion** problem — growing every year with the expansion of cross-border e-commerce, AI-generated product listings, and increasingly sophisticated counterfeit networks that span multiple continents and platforms.

Our platform combines **deep learning**, **large-scale distributed web crawling**, and **automated enforcement workflows** to help brands detect and eliminate counterfeits, unauthorized resellers, domain impersonation, and intellectual property violations — in real time, at global scale.

We don't just find counterfeits. We map the networks behind them, predict where they'll appear next, and automate the entire enforcement lifecycle from detection through takedown to resolution.

<br/>

## 🛡️ Platform

Our platform is composed of six core product modules that work together as a unified brand protection engine:

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🔍 VG Commerce

**Counterfeit Detection & Marketplace Enforcement**

AI-powered scanning of 300+ global e-commerce marketplaces. Our proprietary image recognition, price anomaly detection, and seller behavioral models identify infringing listings with 99.2% accuracy — then automatically generate and submit takedown requests through each platform's enforcement API.

**Key capabilities:**
- Real-time listing surveillance across Amazon, Alibaba, eBay, Shopee, Mercado Libre, Lazada, Etsy, Wish, and 290+ more
- Multi-modal detection: product images, descriptions, pricing patterns, seller metadata
- Automated takedown filing with platform-specific templates
- Appeal management and escalation workflows
- Revenue recovery tracking and ROI reporting

</td>
<td width="50%" valign="top">


### 📋 VG Content

**Digital Content & Copyright Protection**

Continuous monitoring for unauthorized use of copyrighted content, digital assets, brand imagery, and creative materials across the open web, social platforms, and file-sharing networks.

**Key capabilities:**
- Automated DMCA notice generation and submission
- Reverse image search at scale across billions of web pages
- Video and audio fingerprinting for multimedia content
- Social media monitoring: Instagram, Facebook, TikTok, X, YouTube, Pinterest
- Google Search and Shopping delisting requests
- Compliance dashboards with enforcement success rates

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📁 VG Folio

**Trademark Registration & IP Portfolio Management**

End-to-end trademark lifecycle management — from search and filing through monitoring, renewal, and dispute resolution — across 200+ global jurisdictions.

**Key capabilities:**
- AI-powered trademark conflict analysis before filing
- Automated filing through direct integrations with USPTO, EUIPO, WIPO, and 200+ offices
- Continuous trademark watch with real-time alerts
- Renewal management with automated deadline tracking
- Opposition and cancellation proceeding support
- Comprehensive IP portfolio analytics and valuation

</td>
<td width="50%" valign="top">

### 🕵️ VG Intelligence

**Seller Network Analysis & Supply Chain Mapping**

Deep profiling of unauthorized seller networks using link analysis, behavioral clustering, and cross-platform identity resolution to map and disrupt repeat offenders at their source.

**Key capabilities:**
- Cross-platform seller identity resolution (same seller, different storefronts)
- Network graph analysis revealing supplier-distributor relationships
- Geographic clustering and origin country identification
- Repeat offender tracking with historical enforcement data
- Predictive risk scoring: which sellers are likely to relist
- Supply chain mapping from manufacturer to marketplace

</td>
</tr>
<tr>
<td width="50%" valign="top">


### 🌐 VG Domain Shield

**Domain & Impersonation Defense**

Detection and removal of phishing sites, lookalike domains, social media impersonation accounts, and rogue mobile apps that exploit brand identity to deceive consumers and steal revenue.

**Key capabilities:**
- Typosquatting and homograph domain detection
- Phishing site identification and UDRP/URS dispute filing
- Social media impersonation account detection and reporting
- Rogue mobile app monitoring across App Store and Google Play
- SSL certificate transparency monitoring
- Brand mention sentiment analysis and threat classification


</td>
<td width="50%" valign="top">

### ⚖️ VG Enforce

**Offline Enforcement & Legal Coordination**

Bridging digital intelligence with real-world enforcement outcomes. Coordination of physical enforcement actions including customs seizures, test purchases, cease & desist operations, and legal proceedings.

**Key capabilities:**
- Customs recordal and border seizure coordination
- Test purchase programs with chain-of-custody documentation
- Cease & desist letter generation and tracking
- Law enforcement referral packages with evidence compilation
- Raid coordination and post-raid analysis
- Litigation support with digital forensics evidence


</td>
</tr>
</table>

<br/>

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│                              CLIENT LAYER                                       │
│                                                                                 │
│    Platform Dashboard    Marketing Site    Chrome Extension    Public API / SDK  │
│         (React)            (React)           (Manifest V3)       (REST/gRPC)    │
├─────────────────────────────────────────────────────────────────────────────────┤
│                              API GATEWAY                                        │
│                                                                                 │
│       Authentication    Rate Limiting    Load Balancing    Request Routing       │
│          (JWT/SSO)       (Token Bucket)     (Round Robin)     (Path-based)      │
├─────────────────────────────────────────────────────────────────────────────────┤
│                            SERVICE LAYER                                        │
│                                                                                 │
│  ┌───────────────┐  ┌───────────────┐  ┌───────────────┐  ┌───────────────┐    │
│  │   Detection    │  │  Enforcement  │  │    Seller     │  │   Content     │    │
│  │   Engine       │  │   Service     │  │  Intelligence │  │   Monitor     │    │
│  │               │  │               │  │               │  │               │    │
│  │  Image match  │  │  Takedown     │  │  Network      │  │  DMCA         │    │
│  │  Price model  │  │  Appeals      │  │  Graph        │  │  Fingerprint  │    │
│  │  NLP classify │  │  Escalation   │  │  Clustering   │  │  Web crawl    │    │
│  └───────────────┘  └───────────────┘  └───────────────┘  └───────────────┘    │
│                                                                                 │
│  ┌───────────────┐  ┌───────────────┐  ┌───────────────┐  ┌───────────────┐    │
│  │   Trademark   │  │    Domain     │  │   Analytics   │  │   Offline     │    │
│  │   Manager     │  │   Monitor     │  │   Service     │  │   Enforce     │    │
│  │               │  │               │  │               │  │               │    │
│  │  Filing       │  │  DNS watch    │  │  Dashboards   │  │  Test purch.  │    │
│  │  Renewals     │  │  Phishing     │  │  Reports      │  │  Customs      │    │
│  │  Conflicts    │  │  Impersonat.  │  │  ROI metrics  │  │  Legal coord  │    │
│  └───────────────┘  └───────────────┘  └───────────────┘  └───────────────┘    │
├─────────────────────────────────────────────────────────────────────────────────┤
│                          DATA & ML LAYER                                        │
│                                                                                 │
│   Distributed       Image           NLP            Brand          Price         │
│   Crawler Fleet     Similarity      Pipeline       Encoder        Anomaly       │
│   (Scrapy)          (CLIP/FAISS)    (Transformers) (Custom CNN)   (Time-series) │
├─────────────────────────────────────────────────────────────────────────────────┤
│                          INFRASTRUCTURE                                         │
│                                                                                 │
│   AWS (EKS)     Terraform     GitHub Actions     Datadog     PagerDuty         │
│   PostgreSQL    Redis         Kafka              S3          CloudFront        │
└─────────────────────────────────────────────────────────────────────────────────┘
```


<br/>

## 📦 Repositories

We follow a consolidated monorepo-first strategy — starting compact and splitting services as scale demands. Each repository maps cleanly to a team boundary.

<br/>

<table>
<tr>
<td width="25%" align="center">
<br/>
<img width="48" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" />
<br/>
<br/>
<b><a href="https://github.com/ValueGuardAI/valueguard-web">valueguard-web</a></b>
<br/>
<sub>Frontend Monorepo</sub>
<br/>
<br/>
</td>
<td width="75%">

All frontend applications in a single Turborepo workspace:

- **`apps/platform`** — SaaS dashboard for brand clients (detection feeds, enforcement workflows, analytics, IP portfolio management)
- **`apps/marketing`** — Public marketing website (valueguard.ai)
- **`apps/extension`** — Chrome extension for on-page counterfeit flagging and quick reporting
- **`packages/ui`** — Shared design system and component library
- **`packages/config`** — Shared ESLint, TypeScript, and Tailwind configuration

**Stack:** React · TypeScript · Tailwind CSS · Vite · Turborepo · Radix UI · Recharts

</td>
</tr>
<tr>
<td width="25%" align="center">
<br/>
<img width="48" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" />
<br/>
<br/>
<b><a href="https://github.com/ValueGuardAI/valueguard-api">valueguard-api</a></b>
<br/>
<sub>Backend Monolith</sub>
<br/>
<br/>
</td>
<td width="75%">

API gateway and all backend services as a modular monolith — designed for clean extraction into microservices when individual services need independent scaling:

- **`gateway/`** — API gateway with JWT/SSO auth, rate limiting, and request routing
- **`services/detection`** — Counterfeit detection engine orchestration
- **`services/enforcement`** — Takedown submission, appeal handling, escalation
- **`services/intelligence`** — Seller network analysis, cross-platform identity resolution
- **`services/content`** — Content monitoring, DMCA workflows, web scanning
- **`services/trademark`** — IP portfolio management, filing automation, renewal tracking
- **`services/domain`** — Domain monitoring, phishing detection, impersonation defense
- **`services/analytics`** — Reporting, dashboards, ROI metrics, data exports
- **`services/enforce-offline`** — Test purchases, customs coordination, legal workflows

**Stack:** Node.js · Python · PostgreSQL · Redis · Kafka · gRPC · Prisma · Bull MQ

</td>
</tr>
<tr>
<td width="25%" align="center">
<br/>
<img width="48" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" />
<br/>
<br/>
<b><a href="https://github.com/ValueGuardAI/valueguard-ai">valueguard-ai</a></b>
<br/>
<sub>AI, ML & Crawlers</sub>
<br/>
<br/>
</td>
<td width="75%">

Machine learning models, training infrastructure, and the distributed crawling fleet:

- **`models/image-similarity`** — CLIP-based product image matching and visual search (FAISS index)
- **`models/nlp-classifier`** — Transformer models for listing classification, language detection, and entity extraction
- **`models/brand-encoder`** — Custom CNN for brand logo recognition and visual trademark matching
- **`models/price-anomaly`** — Time-series models for price deviation detection and gray market flagging
- **`models/seller-risk`** — Behavioral models for seller risk scoring and relist prediction
- **`crawlers/marketplace`** — Distributed Scrapy/Playwright crawlers for 300+ marketplace feeds
- **`crawlers/web`** — Open web crawler for domain monitoring, social media, and content scanning
- **`pipelines/`** — Airflow DAGs for training, evaluation, and model deployment
- **`evaluation/`** — Benchmark datasets, A/B testing framework, model performance tracking

**Stack:** Python · PyTorch · Transformers · CLIP · FAISS · Scrapy · Playwright · Airflow · MLflow · DVC

</td>
</tr>
<tr>
<td width="25%" align="center">
<br/>
<img width="48" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" alt="Terraform" />
<br/>
<br/>
<b><a href="https://github.com/ValueGuardAI/valueguard-infra">valueguard-infra</a></b>
<br/>
<sub>Infrastructure & Ops</sub>
<br/>
<br/>
</td>
<td width="75%">

Everything that keeps the platform running — infrastructure-as-code, CI/CD, observability, documentation, and developer tooling:

- **`terraform/`** — AWS infrastructure: EKS clusters, RDS, ElastiCache, S3, CloudFront, VPC, IAM
- **`k8s/`** — Kubernetes manifests, Helm charts, namespace configuration
- **`ci/`** — GitHub Actions workflows for build, test, deploy, and release
- **`monitoring/`** — Datadog dashboards, PagerDuty runbooks, SLO definitions
- **`docs/`** — API reference, architecture decision records (ADRs), onboarding guides
- **`sdk/`** — Client SDKs (Python, Node.js, Go) for the ValueGuardAI public API
- **`tools/`** — Internal CLI tools, database migration scripts, seed data generators

**Stack:** Terraform · Kubernetes · Helm · GitHub Actions · Datadog · PagerDuty · AWS CDK

</td>
</tr>
</table>

<br/>

## ⚙️ Tech Stack

<table>
<tr>
<td align="center" width="20%"><b>Layer</b></td>
<td><b>Technologies</b></td>
</tr>
<tr>
<td align="center"><b>Frontend</b></td>
<td>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
<img src="https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white" alt="Turborepo"/>
</td>
</tr>
<tr>
<td align="center"><b>Backend</b></td>
<td>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" alt="Kafka"/>
<img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white" alt="gRPC"/>
</td>
</tr>
<tr>
<td align="center"><b>AI / ML</b></td>
<td>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace"/>
<img src="https://img.shields.io/badge/CLIP-412991?style=flat-square&logo=openai&logoColor=white" alt="CLIP"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" alt="FAISS"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" alt="MLflow"/>
<img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white" alt="Airflow"/>
</td>
</tr>
<tr>
<td align="center"><b>Infra</b></td>
<td>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="K8s"/>
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GH Actions"/>
<img src="https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white" alt="Datadog"/>
</td>
</tr>
</table>

<br/>

## 📊 By the Numbers

<div align="center">

| | | | |
|:---:|:---:|:---:|:---:|
| **300+** | **200+** | **Millions** | **99.2%** |
| Marketplaces Monitored | Trademark Jurisdictions | Listings Scanned Daily | Detection Accuracy |
| | | | |
| **< 60s** | **85%** | **50+** | **24/7** |
| Avg. Detection Latency | Auto-Takedown Success | Countries Covered | Real-Time Monitoring |

</div>

<br/>

## 🌍 Marketplace & Platform Coverage

<details>
<summary><b>E-Commerce Marketplaces (300+)</b></summary>
<br/>

**Global:** Amazon (all regions), eBay, Alibaba, AliExpress, Wish, DHgate, Made-in-China

**Asia Pacific:** Shopee, Lazada, Tokopedia, Bukalapak, JD.com, Taobao, Pinduoduo, Rakuten, Yahoo! Auctions Japan, Coupang, Flipkart, Snapdeal

**Latin America:** Mercado Libre, Americanas, Magazine Luiza, Linio, Falabella

**Europe:** Zalando, Cdiscount, Bol.com, Allegro, Otto, Emag, Wildberries, Ozon

**Middle East & Africa:** Noon, Jumia, Souq, Namshi

**Specialty:** Etsy, Redbubble, Poshmark, Depop, StockX, GOAT, Grailed, OfferUp, Facebook Marketplace

</details>

<details>
<summary><b>Social & Content Platforms</b></summary>
<br/>

**Social Media:** Instagram, Facebook, TikTok, X (Twitter), YouTube, Pinterest, Telegram, WeChat, LINE

**Search & Advertising:** Google Search, Google Shopping, Bing, Baidu, Yandex

**App Stores:** Apple App Store, Google Play Store

**Domain & Web:** WHOIS/DNS monitoring, SSL Certificate Transparency logs, Wayback Machine

</details>

<details>
<summary><b>Enforcement Channels</b></summary>
<br/>

**IP Offices:** USPTO, EUIPO, WIPO, CNIPA, JPO, KIPO, IP Australia, INPI, UKIPO

**Customs:** U.S. CBP, EU Customs, China Customs, Japan Customs, Korean Customs

**Legal Networks:** INTA, IACC, ACG, local law enforcement in 50+ jurisdictions

**Dispute Resolution:** UDRP, URS, platform-specific appeals processes

</details>

<br/>

## 🔒 Security & Compliance

We take the security of our platform and our clients' data seriously. Our infrastructure is built with enterprise-grade security from the ground up.

| Standard | Status |
|:---|:---|
| **SOC 2 Type II** | ✅ Certified |
| **GDPR** | ✅ Compliant |
| **CCPA** | ✅ Compliant |
| **ISO 27001** | 🔄 In Progress |
| **Encryption at Rest** | AES-256 |
| **Encryption in Transit** | TLS 1.3 |
| **Authentication** | SSO / SAML 2.0 / OAuth 2.0 |
| **Access Control** | RBAC with audit logging |
| **Penetration Testing** | Quarterly (third-party) |
| **Uptime SLA** | 99.9% |
| **Data Residency** | US, EU, APAC regions |

<br/>

## 🏭 Industries We Serve

<div align="center">

`Luxury & Fashion` · `Consumer Electronics` · `Pharmaceuticals & Healthcare` · `Sports & Entertainment` · `Automotive & Parts` · `Food & Beverage` · `Software & Digital Media` · `Toys & Gaming` · `Beauty & Cosmetics` · `Industrial Equipment`

</div>

<br/>

## 📬 Get in Touch

<div align="center">

| | |
|:---|:---|
| 🌐 **Website** | [valueguard.ai](https://valueguard.ai) |
| 📖 **Documentation** | [docs.valueguard.ai](https://docs.valueguard.ai) |
| 📧 **General Inquiries** | [hello@valueguard.ai](mailto:hello@valueguard.ai) |
| 🤝 **Partnerships** | [partners@valueguard.ai](mailto:partners@valueguard.ai) |
| 🛡️ **Security** | [security@valueguard.ai](mailto:security@valueguard.ai) |
| 💼 **Careers** | [valueguard.ai/careers](https://valueguard.ai/careers) |

</div>

<br/>

---

<div align="center">

<sub>

**ValueGuardAI** — Protecting brands at the speed of AI.

© 2026 ValueGuardAI. All rights reserved.

</sub>

</div>
