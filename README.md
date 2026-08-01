# Awesome-A-B-Testing-Platform


## Similar Projects to A/B Testing Platforms

**A/B Testing & Experimentation Platforms** enable teams to run controlled experiments (A/B, multivariate, feature experiments), manage feature flags, measure statistical significance, and optimize product or marketing experiences. Leading commercial tools include Optimizely, VWO, AB Tasty, Kameleoon, Convert, LaunchDarkly, Eppo, Statsig, Dynamic Yield, Adobe Target, and related offerings.

Below is a **curated list** of notable platforms and their open-source equivalents. The emphasis is on **open-source** and open-core solutions that support self-hosting, feature flags, experimentation, and statistical analysis.

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing & Free Tier Limits |
| :--- | :--- | :--- |
| **[Optimizely](https://www.optimizely.com/)** | Enterprise experimentation and digital experience platform with advanced A/B testing, personalization, and feature management. | Enterprise pricing (Starts ~$36,000/yr). Free tier: Basic feature flagging only (excludes A/B testing). |
| **[VWO](https://vwo.com/)** | Conversion optimization platform with visual editor, A/B testing, heatmaps, and session insights. | Custom quote. Free tier: None (offers 30-day free trial). |
| **[AB Tasty](https://www.abtasty.com/)** | Experimentation and personalization platform focused on marketing and product teams. | Custom quote (Starts ~$30,000/yr). Free tier: None. |
| **[Kameleoon](https://www.kameleoon.com/)** | AI-powered A/B testing and personalization platform. | Custom quote / Starter plan (~$495/mo). Free tier: None (offers 30-day free trial). |
| **[Convert](https://www.convert.com/)** / Convert Experiences | Privacy-focused A/B testing and experimentation platform. | Growth ($299/mo), Pro ($499/mo), Enterprise (Custom). Free tier: None (offers 15-day free trial). |
| **[LaunchDarkly](https://launchdarkly.com/)** | Leading feature management platform with strong experimentation capabilities (LaunchDarkly Experiments). | Starts at $8.33/user/mo. Free tier: Developer Tier (1 project, 3 environments, limited MAU & experimentation keys). |
| **[Eppo](https://www.geteppo.com/)** | Modern warehouse-native experimentation platform popular with data and product teams. | Custom quote (Starts ~$12,000–$30,000/yr). Free tier: None. |
| **[Statsig](https://www.statsig.com/)** | High-scale experimentation and feature management platform (now associated with OpenAI). | Usage-based pricing. Free tier: Developer Tier (up to 2 million events/month, unlimited seats & flags). |
| **[Dynamic Yield](https://www.dynamicyield.com/)** (Mastercard) | Personalization and experimentation platform. | Custom quote (Starts ~$35,000/yr). Free tier: None. |
| **[Adobe Target](https://business.adobe.com/products/target/adobe-target.html)** | Enterprise personalization and A/B testing solution within the Adobe Experience Cloud. | Custom quote (Enterprise-level). Free tier: None. |

## 🔓 Open-Source Software

### Leading Open-Source Experimentation Platforms
- **[GrowthBook](https://github.com/growthbook/growthbook)** — Fully open-source (MIT) feature flagging and A/B testing platform. Warehouse-native (connects to BigQuery, Snowflake, Redshift, etc.), powerful statistical engine (Bayesian, frequentist, CUPED, sequential testing), visual editor (on some tiers), and self-hostable. One of the strongest open-source alternatives to commercial experimentation tools.
- **[PostHog](https://github.com/PostHog/posthog)** — Open-source product analytics platform that includes robust A/B testing / experimentation, feature flags, session replay, and surveys. Excellent all-in-one self-hosted option.
- **[Unleash](https://github.com/Unleash/unleash)** — Popular open-source feature flag management system with experimentation support. Self-hostable with a strong focus on progressive delivery.
- **[Flagsmith](https://github.com/Flagsmith/flagsmith)** — Open-source feature flags, remote config, and A/B testing platform. Supports self-hosting and multivariate flags.
- **[FeatureHub](https://github.com/featurehub-io/featurehub)** — Cloud-native open-source feature flag, A/B testing, and remote configuration service with real-time streaming updates and multi-language SDKs.
- **[Flagr (openflagr)](https://github.com/openflagr/flagr)** — Lightweight open-source feature flagging, A/B testing, and dynamic configuration microservice written in Go.

### Feature Flag & Experimentation Focused Tools
- **[GO Feature Flag](https://gofeatureflag.org/)** — Fully open-source (MIT) feature flag solution with A/B experimentation support, data exporters, and OpenFeature compatibility. No database required for basic use.
- **[flagd](https://github.com/open-feature/flagd)** — OpenFeature reference implementation / feature flag daemon (Apache 2.0). Headless and highly flexible.
- **[Wasabi](https://github.com/intuit/wasabi)** — Open-source A/B testing platform originally from Intuit (older but still referenced).

### Supporting Standards & Ecosystem
- **[OpenFeature](https://openfeature.dev/)** — Vendor-neutral open standard and SDKs for feature flags. Allows switching between providers (including many of the tools above) without rewriting application code.

### Typical Open-Source Stack
Many teams combine:
1. **Experimentation + Stats** — GrowthBook (warehouse-native analysis)
2. **Feature Flags + Delivery** — Unleash, Flagsmith, or GO Feature Flag
3. **Product Analytics + Experiments** — PostHog
4. **Standards layer** — OpenFeature for portability

This approach provides full data ownership, avoids vendor lock-in, and delivers enterprise-grade experimentation capabilities at significantly lower cost.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects that support A/B testing, feature flags, or statistical experimentation.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open-source experimentation tooling keeps getting better! 🧪
