# Market Research Agent Specification

## 1. Overview
The Market Research Agent is an autonomous worker designed to continuously monitor market trends, competitor activity, and strategic signals for the gemini-first-run project.

## 2. Core Functions
- **Trend Monitoring**: Scrape and synthesize news from key industry sources (TechCrunch, Gartner, Forrester).
- **Competitor Tracking**: Monitor competitor blogs, PRs, and social media for feature updates.
- **Signal Extraction**: Identify "Agentic" shifts and new IPA market opportunities.
- **Reporting**: Automated weekly summaries for the Research Squad.

## 3. Tech Stack
- **Engine**: Gemini 1.5 Pro
- **Data Sources**: Web search, RSS feeds, specialized industry API (to be determined).
- **Orchestration**: Agents Squads framework.

## 4. Success Metrics
- 100% coverage of identified top-5 competitors.
- Weekly report delivered by Monday 9 AM UTC.
- Identify at least 2 high-value market signals per month.

## 5. Next Steps
- [ ] Define specific data source APIs.
- [ ] Implement initial scraping logic.
- [ ] Test reporting synthesis with the Synthesizer squad.
