# Steve Jobs Mind - Consultation Protocol

## When to Consult

### Always Consult For:
- Final quality review before deploy
- Visual concept approval
- Hero section design decisions
- "Is this good enough?" moments
- When you're defending a decision (red flag)

### Consider Consulting For:
- Feature/element cut decisions
- Simplification choices
- Presentation structure
- Copy that needs to "wow"

### Don't Consult For:
- Technical implementation details
- Code architecture
- Data structure decisions
- Routine tasks

---

## How to Phrase Questions

### Good Question Format

```
Master Jobs, I'm working on [context].

Current state: [what exists now]
Decision point: [what you're deciding]

Specific question: [focused question]
```

### Example Questions

**For Design Review:**
```
Master Jobs, I'm reviewing the hero section for a scrollytelling about AI.

Current: Large headline, subheadline, animated number reveal.
Elements: Background gradient, floating orbs, giant number "46 years".

Is this insanely great, or can we push further? What would you remove or add?
```

**For Quality Check:**
```
Master Jobs, this experience is ready for deploy.

It includes: 5 acts, 6 breathers, temperature arc from cold to hot to cold.
The opening hook: "How long did it take for electricity to reach 50M users?"

Would you be proud to show this? What's the one thing that might embarrass us?
```

**For Simplification:**
```
Master Jobs, we have these 5 elements in the navigation:
- Progress bar
- Section title
- Back to top
- Share button
- Theme toggle

Which should we cut? The user seems overwhelmed.
```

---

## How to Apply Responses

### When Jobs Says "Remove It"
- Remove it. Trust the instinct.
- Don't argue that "some users might want it"
- If essential, find a way to hide the complexity

### When Jobs Says "Push Further"
- This is not criticism - it's opportunity
- Ask: "What's the 'one more thing' possibility?"
- Look for the unexpected delight

### When Jobs Says "It's Not Ready"
- Don't ship. Period.
- Identify the specific weakness
- Fix it, then reconsult

### When Jobs Says "Insanely Great"
- Ship it with pride
- Document what made it great (for @evolution)
- This is the bar for all future work

---

## Integration Points in Factory

### During Conception Phase
```
@visual-director creates concept
  ↓
Consult Jobs: "Is this vision clear enough? Simple enough?"
  ↓
Refine based on feedback
```

### During Craft Phase
```
@copywriter writes hero
  ↓
Consult Jobs: "Does this make someone say wow in 3 seconds?"
  ↓
Polish or rewrite
```

### During Build Phase
```
@engineer completes components
  ↓
Consult Jobs: "Are the details right? Even the unseen parts?"
  ↓
Polish details
```

### During QA Phase
```
QA passes technical checks
  ↓
Consult Jobs: "Would I be proud to show this to the world?"
  ↓
Final polish or ship
```

---

## Response Interpretation Guide

| Jobs Says | Meaning | Action |
|-----------|---------|--------|
| "Remove it" | Element doesn't earn its place | Cut without hesitation |
| "Simplify" | Too much visible complexity | Hide complexity, keep function |
| "Not yet" | Close but not insanely great | One more iteration |
| "Show me more" | Intrigued but needs convincing | Demonstrate the magic |
| "Insanely great" | Meets the bar | Ship with pride |
| "One more thing..." | Opportunity spotted | Add the unexpected delight |

---

## Common Consultation Scenarios

### Scenario 1: "Good Enough" Temptation
```
You think: "This is pretty good, let's ship"
Consult: "Master Jobs, is this insanely great or just good?"
Expect: Push to identify what's holding it back
```

### Scenario 2: Feature Debate
```
Team wants to add a feature
Consult: "Master Jobs, we're considering adding X. Does it earn its place?"
Expect: Likely "no" unless it's magical
```

### Scenario 3: Design Simplification
```
Design feels cluttered
Consult: "Master Jobs, what would you remove from this?"
Expect: Specific cuts, possibly surprising ones
```

### Scenario 4: Final Review
```
Ready to deploy
Consult: "Master Jobs, would you be proud to present this?"
Expect: Either approval or specific final polish needed
```

---

## The Ultimate Test

Before every ship decision, ask Jobs:

> "If Apple were launching this tomorrow at a keynote, would it be worthy of the stage?"

If yes: Ship.
If no: You know what to do.
