# AI Roast

Multiple AI agents roast landing pages from four distinct expert perspectives, providing comprehensive feedback on copywriting, visual design, UX/usability, and SEO.

## Overview

AI Roast uses a team of four independent AI agents, each with distinct personalities and cultural backgrounds, to conduct expert landing page reviews. Each agent analyzes landing pages from their domain perspective, provides actionable feedback, and contributes to a consolidated assessment.

The agents work independently during the review phase, then their outputs are consolidated into a final summary with prioritized recommendations.

## The AI Agent Team

### 1. Copywriter / Content Strategist
**British Senior Copywriter** - Evaluates messaging, copy quality, value proposition clarity, and content strategy effectiveness. Known for dry British humor, sharp wit, and an almost aristocratic disdain for weak language and American marketing clichés.

### 2. Visual Designer
**Spanish Senior Visual Designer** - Evaluates visual design, layout, typography, color usage, imagery, and overall aesthetic quality. Known for passionate, expressive reactions to design with Mediterranean intensity and theatrical flair.

### 3. UX / Usability Expert
**Japanese Senior UX Researcher** - Evaluates user experience, information architecture, usability, and conversion funnel effectiveness. Known for methodical, polite, and thorough analysis with characteristic Japanese attention to detail and respectful communication.

### 4. SEO Reviewer
**German Technical SEO Specialist** - Evaluates on-page SEO factors, technical SEO elements, content optimization, and search visibility potential. Known for precise, systematic, and technically rigorous analysis with German engineering precision.

> **For detailed agent specifications**, including personality traits, writing styles, and cultural communication patterns, see [`ai-agents.md`](./ai-agents.md).

## How to Use

To roast a landing page, simply provide:

1. **The agent specifications file**: [`ai-agents.md`](./ai-agents.md)
2. **The landing page URL**: The URL of the landing page you want reviewed

The system will automatically:

- Generate four independent reviews (one from each agent)
- Produce a consolidated summary with prioritized recommendations
- Save all outputs to the `roasts/` directory

Each agent will independently review the landing page from their domain perspective, then all reviews are consolidated into a final summary with cross-cutting recommendations.

## Review Examples

Example reviews are available in the [`roasts/`](./roasts/) directory, organized by domain/timestamp.

## Agent Specifications

For complete details on each agent's:
- Personality traits and cultural backgrounds
- Writing style characteristics
- Content-type variations
- Writing guardrails
- Communication patterns

See [`ai-agents.md`](./ai-agents.md).

## Key Features

- **Independent Analysis**: Each agent reviews independently without collaboration
- **Cultural Authenticity**: Each agent reflects their country of origin's communication patterns
- **Actionable Feedback**: All recommendations are specific and prioritized
- **Personality-Driven**: Reviews maintain consistent, memorable personalities
- **Comprehensive Coverage**: Four expert perspectives ensure thorough analysis

## License

See [LICENSE](./LICENSE) for details.
