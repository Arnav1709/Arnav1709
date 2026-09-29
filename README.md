# Arnav Kumar

SDE Intern @ Coupang | Founding Engineer @ Flowbee AI | Software Engineer Intern @ 1000xdev | Open Source Contributor @ Learning Unlimited (ESP-Website)

[![LinkedIn Badge](https://img.shields.io/badge/-arnavkumar-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/arnav-kumar-9691a61b4/)](https://www.linkedin.com/in/arnav-kumar-9691a61b4/)
[![GitHub Badge](https://img.shields.io/badge/-Arnav1709-181717?style=flat-square&logo=github&logoColor=white&link=https://github.com/Arnav1709)](https://github.com/Arnav1709)

## Professional Experience

### Coupang — SDE Intern
**Transport Department, First & Middle Mile Team | June 2026 – Present**

- Improved availability across 15+ production API endpoints to 100%, an average increase of 4.25% over a 30-day rolling window, by handling invalid input and resolving duplicate-row race conditions.
- Reduced p99 latency by an average of 1.5 seconds across three Excel-export API endpoints by fixing N+1 queries and fetching only the columns used in the export.
- Reduced CPU spikes under production workloads by tuning G1GC settings, increasing `MaxGCPauseMillis` from 30 to 200 and `ParallelGCThreads` from 4 to 8.
- Removed a redundant endpoint that fetched 190,000 rows for an autocomplete feature that had been replaced with a plain-text input.
- Optimized database query which led to reducing DB load.

### Flowbee AI — Founding Engineer
**Content intelligence and personal branding platform | May 2025 – January 2026**

- Built queue-based background processing for compute-heavy workflows.
- Reduced app startup time by 70% (15 seconds to 4 seconds) by moving network calls off the UI thread.
- Designed an AI-driven theme and element classification pipeline using LangChain with Claude and OpenAI, integrated into a production ETL workflow.
- Migrated onboarding from client-side to server-side processing with live status updates through Firebase, preventing failures when users closed the app mid-flow.
- Implemented over-the-air updates with Shorebird, push notifications with OneSignal, and offline-first persistence with Hive.
- Integrated Mixpanel, Sentry, and AWS CloudWatch for analytics, monitoring, and error tracking, and embedded a LiveKit voice agent in the Flutter app.

### 1000xdev — Software Engineer Intern
**LLM-powered deal discovery and web data pipeline | December 2025 – January 2026**

- Implemented BullMQ background queues for scheduled web scraping and data ingestion.
- Designed a four-stage LLM pipeline using OpenRouter to normalize, filter, and rank product data.
- Integrated ScrapingBee and ScraperAPI to extract structured data from product and search-results pages.

## Open Source

### Learning Unlimited — ESP-Website
**Open Source Contributor | February 2026 – Present**

- Contributed 85 pull requests, with 77 merged, across backend development, performance optimization, and CI/CD infrastructure.
- Migrated the development environment from Vagrant to Docker Compose, improving reproducibility and contributor onboarding.
- Fixed N+1 query bottlenecks and added transactional integrity with Django's `transaction.atomic` to prevent partial updates in multi-step workflows.
- Strengthened CI with dependency caching, concurrency controls, least-privilege permissions, and faster lint feedback.
