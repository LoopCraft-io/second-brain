# Content Engine

## Purpose
Generate ideas and create content (blog, newsletter, podcast) informed by your knowledge base and current trends.

## Trigger
`/run content [type]`

Types: `blog`, `newsletter`, `podcast`, `all`

## Workflow

### Phase 1: Ideation
Pull from multiple sources:
1. **Knowledge base** - What have you learned recently?
2. **Briefs** - What's trending in your sources?
3. **Goals** - What would advance your goals?
4. **Gaps** - What questions keep coming up?

Generate 5-10 ideas ranked by:
- Relevance to audience
- Your unique angle
- Timeliness
- Effort required

### Phase 2: Research
For chosen topic:
- Pull related [[Knowledge]] notes
- `/gather [topic]` for fresh perspectives
- Identify contrarian angles
- Find supporting examples/data

### Phase 3: Structure
Create outline based on content type:

**Blog Post**
- Hook (problem/question)
- Context (why now)
- Main argument (3 points max)
- Evidence/examples
- Takeaway/CTA

**Newsletter**
- Opener (personal/timely)
- Main piece
- Quick hits (3-5 links)
- Ask/CTA

**Podcast**
- Cold open hook
- Guest intro (if applicable)
- 3-4 main segments
- Takeaways
- Next episode tease

### Phase 4: Draft
- Write in your voice (learn from past content)
- Embed knowledge links
- Include specific examples
- Add visuals/formatting notes

### Phase 5: Polish
- Read aloud check
- Cut 20%
- Strengthen opening
- Clear CTA
- SEO (blog) / Subject line (newsletter)

## Content Calendar
`04-Outputs/content/calendar.md`
- Weekly themes
- Publication schedule
- Repurposing plan
- Promotion checklist

## Idea Bank
`04-Outputs/content/ideas.md`
- Captured ideas (from `/in`)
- Ranked backlog
- Seasonal/timely hooks
- Series concepts

## Voice & Style
Learn from user's past content:
- Sentence length patterns
- Common phrases
- Humor style
- Technical depth
- Personal disclosure level

Store in `05-System/preferences.md`

## Repurposing Matrix
| Source | → Blog | → Newsletter | → Podcast | → Social |
|--------|--------|--------------|-----------|----------|
| Blog   | -      | Summarize    | Discuss   | Quotes   |
| Newsletter | Expand | - | Topics | Highlights |
| Podcast | Transcript → post | Key points | - | Clips |

## Integration with Summaries
Daily/weekly summary includes:
- Trending topics in your niche
- Content performance
- Ideas surfaced from knowledge
- Upcoming calendar items
