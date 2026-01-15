# Education Engine

## Purpose
Structured learning paths for any topic, optimized for retention and application.

## Trigger
`/run education [topic]`

## Workflow

### Phase 1: Assess
1. What do you already know?
2. Why learn this? (goal connection)
3. Time available?
4. Preferred learning style?

### Phase 2: Map
Generate learning path in `01-Goals/learning-[topic]/path.md`:
- Core concepts (must know)
- Supporting skills
- Advanced topics
- Practical projects

### Phase 3: Curate
Pull from Knowledge base + gather:
- Best resources (articles, videos, courses)
- Estimated time per resource
- Suggested sequence
- Spaced repetition schedule

### Phase 4: Learn
For each session:
- Pre-read/watch assignment
- Active note-taking → `02-Knowledge/[topic]/`
- Summary in own words
- Connection to existing knowledge
- Application exercise

### Phase 5: Apply
- Mini-project ideas
- Real-world application to current goals
- Teaching opportunity (blog post, explain to someone)

## Learning Modes

### Deep Dive (1-2 weeks)
Intensive focus on one topic
- 2-3 hours daily
- Project-based outcome
- Full concept map

### Continuous (ongoing)
Steady skill building
- 30 min daily
- Spaced repetition
- Incremental projects

### Just-in-Time (as needed)
Solve immediate problem
- Targeted search
- Quick concept grab
- Apply immediately

## Note Templates

### Concept Note
```markdown
# [Concept Name]

## One-line summary

## Key points
- 
- 
- 

## Examples

## Connections
- [[Related concept]]

## Questions

## Source
```

### Session Log
```markdown
# Learning Session - [Date]

## Topic: 

## Time spent: 

## Key takeaways
1. 
2. 
3. 

## Still confused about

## Next session focus
```

## Integration with Goals
- Link learning to active goals
- Apply new knowledge immediately
- Track skill development over time
- Surface relevant learnings in summaries
