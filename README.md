### Plamen Markov – Senior Backend & AI Engineer

[plamen.lynxlake.org](https://plamen.lynxlake.org/) – profile, projects and an AI assistant that answers questions about my work.

I build LLM features into production software and own them after launch: a Claude plugin held to an LLM-judge eval suite, a tool-calling agent that is never allowed to compute a figure itself, a read-only ChatGPT connector into a live insurance back office, an MCP server published on npm, and vision OCR. Before that, two decades of remote backend work, most of it as the engineer responsible for the whole system – one platform for 13 years, from architecture and data model to rollout and maintenance. PHP and Laravel are the foundation; TypeScript and LLM integration are where the work is heading.

Pleven, Bulgaria (Europe/Sofia).

#### AI work, with numbers

- [Forensic fire reports with a Claude plugin](https://github.com/plamen911/fire-service-skills/blob/main/docs/case-study-eptz.md) – a court-format expert report drafted from photos of 15–20 key pages of a 45–70-page case file in 10–15 minutes instead of 5–6 hours. An eval suite with an LLM judge measures the output: it catches 6 of 6 planted fabrications. Personal-data checks are enforced in code.
- ChatGPT connector into a live insurance back office – a read-only MCP server on Laravel with OAuth 2.1: each employee signs in with their own account, every call runs as them and is logged, and the tools wrap the app's own services so ChatGPT and the app cannot disagree on a figure. Client code, described on [my site](https://plamen.lynxlake.org/#project-chatgpt-connector).
- [Automated motor-insurance check over MCP](https://github.com/plamen911/go-insurance-checker/blob/main/docs/case-study.md) – an MCP server on npm (`npx -y go-insurance-checker`) that automates the check in the official register, with three interchangeable data sources behind one interface.

#### Also

- Earlier, fire-expert.uk – a Bulgarian RAG assistant (PostgreSQL + pgvector, hybrid search, Cohere rerank), built and run end to end; no longer maintained.
- ADR Zone – an offline dangerous-goods reference for emergency responders, React Native / Expo, on the App Store.

Available for remote B2B contract work, part-time to full-time · [Website](https://plamen.lynxlake.org/) · [LinkedIn](https://www.linkedin.com/in/plamen-markov-14254965/)
