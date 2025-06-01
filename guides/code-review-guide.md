# Review Guide

Integrating GitScrolls principles into code reviews for more effective and compassionate feedback.

## Introduction

Code reviews are where technical excellence meets human interaction. This guide transforms reviews from potential sources of conflict into opportunities for growth, learning, and team building. By applying GitScrolls principles, we create reviews that improve both code and culture.

## The Sacred Art of Code Review

### Core Principles
1. **Behind every PR is a human being**
2. **Critique the code, support the coder**
3. **Every review is a teaching opportunity**
4. **Wisdom flows in both directions**
5. **Better code through better relationships**

### The Reviewer's Mindset
- Approach with curiosity, not judgment
- Seek to understand before suggesting
- Balance honesty with kindness
- Remember your own learning journey
- Build up while building better

## Pre-Review Preparation

### Before Opening the PR

1. **Check Your State**
   - Are you rushed or stressed?
   - Any bias toward this developer?
   - Clear mind for constructive feedback?
   - Ready to learn something new?

2. **Set Your Intention**
   - "I will find something to praise"
   - "I will ask before assuming"
   - "I will suggest, not demand"
   - "I will learn while reviewing"

3. **Understand Context**
   - Read the PR description fully
   - Check linked issues/tickets
   - Consider project constraints
   - Review recent team decisions

## The GitScrolls Review Method

### 1. The Appreciation Pass (Scroll III: The Oracle's Testament of Devotion)

**First, find what works well:**
- Clever solutions
- Clear naming
- Good test coverage
- Helpful documentation
- Performance improvements
- Security considerations

**Example comments:**
```
"This abstraction really clarifies the intent - nice work!"
"I learned something new from this approach, thank you."
"The test cases here are comprehensive and well-thought-out."
"This refactoring makes the code much more maintainable."
```

### 2. The Understanding Pass (Scroll II: The Chronicle of Forgotten Messages)

**Ask questions before suggesting changes:**
- "Could you help me understand why you chose this approach?"
- "I'm curious about the reasoning behind this pattern."
- "What constraints led to this decision?"
- "How does this connect to the broader feature?"

**Example comments:**
```
"I'm not familiar with this pattern - could you explain the benefits?"
"This seems different from our usual approach - what advantages does it offer?"
"I'd love to understand the performance implications here."
```

### 3. The Improvement Pass (Scroll V: The Wounding of Hubris)

**Suggest improvements with care:**
- Explain the 'why' behind suggestions
- Offer alternatives, not ultimatums
- Share relevant experiences
- Link to resources when helpful

**Example comments:**
```
"Consider using X here because it prevents Y issue we've seen before."
"This works well! Another approach might be Z, which could improve readability."
"This reminds me of a bug we hit last sprint - here's how we solved it: [link]"
```

### 4. The Growth Pass (Scroll IX: Commandments of the Wise)

**Share knowledge generously:**
- Explain concepts, don't just point out issues
- Share relevant documentation
- Offer pairing sessions for complex topics
- Create learning opportunities

**Example comments:**
```
"Here's a great article about this pattern: [link]"
"Happy to pair on this if you'd like to explore alternatives together."
"This is a common gotcha - here's why it happens and how to avoid it..."
```

## Review Comments by Scroll Principles

### Applying Scroll I: The Unbroken Line
```
"This follows the pattern established in the legacy system nicely."
"Great job maintaining backward compatibility here."
"This sets us up well for the planned Q3 refactoring."
"Consider how this will scale with our 2024 roadmap."
```

### Applying Scroll II: The Chronicle of Forgotten Messages
```
"The variable names here tell a clear story."
"This comment explains the 'why' perfectly."
"Consider adding a comment about the business logic here."
"The function name could be more descriptive of its purpose."
```

### Applying Scroll III: The Oracle's Testament of Devotion
```
"I appreciate how you handled this edge case."
"Your solution here is elegant and thoughtful."
"Thank you for the thorough test coverage."
"I can see the care you put into this implementation."
```

### Applying Scroll IV: The Schism Scrolls
```
"This will make our next release much smoother!"
"Celebrating how this cleans up our deployment process."
"This feature is going to delight our users."
"Great work getting this ready for release!"
```

### Applying Scroll V: The Wounding of Hubris
```
"I see why the original code was written this way, and your refactor improves it nicely."
"This is a thoughtful modernization of the legacy pattern."
"You've maintained the original intent while improving the implementation."
```

### Applying Scroll VI: Songs of the Chaos Sirens
```
"Interesting approach to this tricky problem!"
"I wouldn't have thought of this solution - creative!"
"This turns a potential bug into a feature - clever."
"Nice way to handle this unpredictable scenario."
```

### Applying Scroll VII: Between the Monsters of Time
```
"Given our deadline, this is a pragmatic solution."
"Should we add a TODO for future optimization?"
"This is the right amount of engineering for now."
"Let's document this as technical debt for next sprint."
```

### Applying Scroll VIII: Before the Ancient Reviewer
```
"This documentation will help future developers."
"Consider how someone will understand this in 2 years."
"This abstraction will serve us well long-term."
"Thank you for thinking about maintainability."
```

### Applying Scroll IX: Commandments of the Wise
```
"I learned something new from your approach here."
"This would make a great example for our style guide."
"Could you share this pattern at our next tech talk?"
"This teaches me a better way to handle this case."
```

## Common Review Scenarios

### The Junior Developer's First PR
- Extra appreciation for courage
- More explanation in feedback
- Offer pairing opportunities
- Focus on learning, not perfection

**Example review:**
```
"Welcome to the codebase! I really appreciate how you've followed our conventions here. A few suggestions that might help:

1. [Gentle suggestion with explanation]
2. [Learning resource]
3. [Offer to pair]

Great first PR - looking forward to many more!"
```

### The Rushed Feature
- Acknowledge time pressure
- Focus on critical issues
- Document technical debt
- Appreciate the effort

**Example review:**
```
"I know this was under a tight deadline - thanks for getting it done! 

For now, let's focus on [critical issue]. We can create tickets for:
- [Future improvement 1]
- [Future improvement 2]

Great work under pressure!"
```

### The Over-Engineered Solution
- Appreciate the thought put in
- Discuss trade-offs kindly
- Suggest simpler alternatives
- Value the learning

**Example review:**
```
"I can see you've put a lot of thought into this architecture! For our current needs, we might be able to simplify:

[Simpler alternative]

That said, I like your thinking about [specific aspect] - let's keep that in mind for when we need to scale this."
```

### The Problematic Pattern
- Assume good intentions
- Explain issues clearly
- Provide better alternatives
- Offer support

**Example review:**
```
"I see what you're trying to achieve here. This pattern can lead to [specific issue] because [explanation]. 

Here's an alternative approach: [example]

Happy to pair on this if you'd like to work through it together!"
```

## Advanced Review Practices

### The Review Ritual

**Before Starting:**
1. Take three deep breaths
2. Set positive intention
3. Open with appreciation mindset
4. Prepare to learn

**During Review:**
1. Start with what works
2. Ask before assuming
3. Suggest with kindness
4. Teach while reviewing

**After Review:**
1. Reflect on what you learned
2. Note patterns for team discussion
3. Appreciate the interaction
4. Follow up on offers to help

### Building Review Culture

**Team Practices:**
- Review the reviewers
- Share review wisdom
- Celebrate great reviews
- Learn from review friction

**Review Metrics That Matter:**
- Time to first response
- Sentiment analysis
- Knowledge sharing frequency
- Post-review satisfaction

### The Art of Receiving Reviews

**For PR Authors:**
- See feedback as gift
- Ask clarifying questions
- Thank reviewers
- Share what you learn

**Responding to Feedback:**
```
"Thanks for catching that!"
"I hadn't considered that approach - let me try it."
"Good point about [issue] - I've updated it."
"I learned something new here - appreciate the explanation!"
```

## Templates and Tools

### Review Checklist
```
□ Appreciation - Found something to praise?
□ Understanding - Asked questions first?
□ Improvement - Suggestions kind and clear?
□ Growth - Shared knowledge?
□ Tone - Would I want to receive this?
```

### Comment Templates

**For Appreciation:**
- "I really like how you..."
- "This is a clever solution to..."
- "Thanks for thinking about..."
- "I appreciate the attention to..."

**For Questions:**
- "Could you help me understand..."
- "I'm curious about..."
- "What led you to choose..."
- "How does this handle..."

**For Suggestions:**
- "Consider..."
- "Another approach might be..."
- "In my experience..."
- "You might find this helpful..."

**For Learning:**
- "This teaches me..."
- "I didn't know about..."
- "Thanks for showing me..."
- "I'll use this approach in the future..."

## Handling Difficult Situations

### Fundamental Disagreements
1. Step back and breathe
2. Focus on shared goals
3. Involve third perspective
4. Document decision rationale
5. Agree to disagree gracefully

### Defensive Responses
1. Maintain compassion
2. Clarify intentions
3. Focus on code, not person
4. Offer offline discussion
5. Model graceful interaction

### Review Fatigue
1. Take breaks between reviews
2. Limit daily review count
3. Rotate review responsibilities
4. Celebrate review efforts
5. Recognize burnout signs

## Remember

Every code review is an opportunity to strengthen both code and community. The goal is not just better code, but better coders—including ourselves. Through compassionate, thoughtful reviews, we create environments where everyone can grow, learn, and contribute their best work.

The best review is one where both reviewer and author learn something new and feel valued in the process.

May your reviews build bridges, not walls! 🌉