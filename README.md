# Jared Yankee | Full-Stack & Integrations Engineer

Specializing in custom enterprise API integrations, webhook automation, and scalable backend workflows. 

[LinkedIn](https://linkedin.com/in/jaredyankee) | [Email](mailto:hello@jaredyankee.com) | [Website](https://jaredyankee.com)

## 🚀 About Me
I am a Software Developer specializing in complex system integrations. I bridge the gaps between enterprise platforms like **HubSpot, NetSuite, Stripe, and BigCommerce**, engineering the robust data pipelines that keep businesses synchronized. My expertise lies in designing loop-preventing syncs, building automated lead qualification engines, and reconciling distributed records against a central source of truth.

I thrive in autonomous environments where I can own technical architecture end-to-end, translating complex business logic into clean, production-ready systems.

## 🛠️ Deep-Dive Project: Seyona.ai
I am currently building **Seyona.ai**, an SEO/AEO platform that automates FAQ generation and manages dynamic client-side injections. To handle heavy scraping and generation workloads asynchronously, I built a pipeline that ingests data, queues it via a database-driven request architecture, and processes it across a three-model AI workflow:

1. **Brand Profile Engine:** Generates a sitewide master context detailing core business offerings, brand voice, and structured reference mappings.
2. **Trend Analysis Pipeline:** Analyzes page content against search trends, outputting high-opportunity targets with clear rationale, URL citations, and algorithmic confidence scoring.
3. **Optimized FAQ Generation:** Ingests the trend data, page content, and brand profile to synthesize SEO/AEO-optimized question-and-answer schemas ready for server-side rendering or widget injection.

## 💻 Engineering Highlights
* **Two-Way HubSpot–NetSuite Order Sync:** Designed a bi-directional data pipeline featuring custom loop-prevention logic to permanently eliminate cascading webhook cycles.
* **Asynchronous Request Pipeline:** Re-architected Seyona's main ingest pipeline to store incoming payloads securely in Postgres and process them asynchronously via scheduled serverless functions.
* **Serverless PDF Generation Engine:** Configured and deployed headless Chromium within a strict Netlify function environment to dynamically generate server-side PDF invoices for complex BigCommerce subscription cycles.
* **Automated Lead Qualifier:** Developed a pre-ingest validation layer for HubSpot form submissions that evaluates form data and geographical origin, dropping unqualified leads before they taint core CRM records.
