# AI Skills Library

A centralized library of AI skill files for use across n8n workflows via MCP or HTTP Request nodes.

## How to Use in n8n

In any Anthropic node, fetch a skill via HTTP Request:
```
GET https://raw.githubusercontent.com/YOUR_USERNAME/ai-skills-library/main/seo/on-page-seo.md
```
Then inject the response body into the System Prompt field.

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

---

*More skill categories coming: marketing, design, documents, ads*
