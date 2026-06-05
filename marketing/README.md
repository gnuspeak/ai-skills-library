# AI Skills Library

A centralized library of AI skill files for use across n8n workflows via HTTP Request nodes.

## How to Use in n8n

In any Anthropic node, fetch a skill via HTTP Request:
```
GET https://raw.githubusercontent.com/gnuspeak/ai-skills-library/main/seo/on-page-seo.md
```
Then inject the response body into the System Prompt field.

### URL Pattern
```
https://raw.githubusercontent.com/gnuspeak/ai-skills-library/main/{category}/{skill-name}.md
```

---

## Skills Index

### SEO (`/seo`)

| Skill | File | Description |
|-------|------|-------------|
| On-Page SEO | `seo/on-page-seo.md` | Optimize a specific page for search |
| SEO Audit | `seo/seo-audit.md` | Full site SEO audit |
| Content Brief | `seo/content-brief.md` | Plan an article before writing |
| Content Strategy | `seo/content-strategy.md` | Plan what content to create |
| Content Translation | `seo/content-translation.md` | Multilingual & localization SEO |
| Keyword Clustering | `seo/keyword-clustering.md` | Group keywords into topic clusters |
| Internal Linking | `seo/internal-linking.md` | Improve site link structure |
| Broken Links | `seo/broken-links.md` | Find and fix dead links |
| Schema Markup | `seo/schema-markup.md` | Generate JSON-LD structured data |
| Technical SEO | `seo/technical-seo.md` | Crawlability, speed, indexation |
| AI Visibility | `seo/ai-visibility.md` | Appear in AI-generated answers |

### Marketing (`/marketing`)

| Skill | File | Description |
|-------|------|-------------|
| Brand Review | `marketing/brand-review.md` | Review content against brand voice |
| Campaign Plan | `marketing/campaign-plan.md` | Full campaign brief and calendar |
| Competitive Brief | `marketing/competitive-brief.md` | Competitor research and positioning |
| Content Creation | `marketing/content-creation.md` | Draft marketing content across channels |
| Draft Content | `marketing/draft-content.md` | Blog posts, social, email, landing pages |
| Email Sequence | `marketing/email-sequence.md` | Multi-email drip sequences |
| Performance Report | `marketing/performance-report.md` | Marketing metrics and analysis |
| SEO Audit | `marketing/seo-audit.md` | Marketing-focused SEO audit |

---

*More skill categories coming: design, documents, ads*
