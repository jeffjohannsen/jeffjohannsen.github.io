# Copilot Instructions for jeffjohannsen.github.io

## Repository Purpose
This is a dual-purpose repository:
1. **Public Portfolio Site** - GitHub Pages site at jeffjohannsen.com showcasing data science projects
2. **Private Career Management** - Local-only `career/` folder (git-ignored) for resumes, job tracking, etc.

## Tech Stack
- **Static Site Generator**: Jekyll (via GitHub Pages gem)
- **CSS Framework**: Tailwind CSS v2.2.7 (CDN via `main.css`)
- **Typography**: Inter font family
- **Hosting**: GitHub Pages
- **Analytics**: Google Analytics (G-YT0T4V3FHG)

## Project Structure
```
index.html          # Main portfolio page (primary content)
main.css            # Tailwind CSS styles
inter.css           # Inter font imports
images/             # Project screenshots and profile photo
_config.yml         # Jekyll configuration and SEO metadata
Gemfile             # Ruby dependencies (github-pages gem)
career/             # PRIVATE - local only, never commit
```

## Portfolio Content Guidelines
- **Location**: Currently Portland, OR
- **Role**: Data Scientist • AI Engineer
- **Featured Project**: NBA AI (https://nba-ai.us/)
- **Key Skills**: Python, SQL, AWS, Deep Learning, GenAI, PyTorch, Pandas, Sklearn, AutoML, Flask, Scrapy

When updating project descriptions:
- Verify current state of referenced GitHub repos before updating descriptions
- Use HTTPS links (not HTTP) for external sites
- Keep descriptions concise but informative with bullet points for key features

## Career Folder (Private)
The `career/` directory is git-ignored and contains private career management files:
- Resumes and cover letters
- Job application tracking
- Interview notes
- Salary research
- Networking contacts

**Never commit or reference specific content from this folder in public commits.**

## Code Style Preferences
- HTML: Use Tailwind utility classes, maintain consistent indentation
- Keep inline styles minimal; prefer Tailwind classes
- Use semantic HTML where appropriate
- External links should have `target="_blank"`

## Related Repositories
- [NBA-Betting/NBA_AI](https://github.com/NBA-Betting/NBA_AI) - Featured project
- [NBA-Betting/NBA_Betting](https://github.com/NBA-Betting/NBA_Betting) - Legacy project (deprecated)
- [jeffjohannsen/Predicting-Yelp-Review-Quality](https://github.com/jeffjohannsen/Predicting-Yelp-Review-Quality)
- [jeffjohannsen/Fraud_Detection](https://github.com/jeffjohannsen/Fraud_Detection)
