# Algorithm Models

Computational approaches to human problems. Based on "Algorithms to Live By" by Brian Christian and Tom Griffiths.

## Contents
- [Search & Selection](#search--selection)
- [Sorting & Organization](#sorting--organization)
- [Scheduling & Time](#scheduling--time)
- [Optimization & Adaptation](#optimization--adaptation)

---

## Search & Selection

### 1. Optimal Stopping (37% Rule)
**Principle**: When to stop searching and commit.
- Explore first 37% of options (without committing)
- Then commit to first option better than all explored
- Balances exploration vs exploitation
- **Applications**: Hiring, dating, apartment hunting
- **Example**: Interview 37 candidates, then hire first better than all previous

### 2. Look-Then-Leap Rule
**Principle**: Separate exploration phase from commitment phase.
- During look phase: gather information, don't commit
- At threshold: switch to leap mode
- Never go back to rejected options
- **Example**: Researching cars for a month, then buying first good deal

### 3. Secretary Problem Variants
**Principle**: Optimal stopping under different conditions.
- Known pool size: 37% rule
- Unknown pool size: different thresholds
- Can return to candidates: can be more selective
- Cost of search: stop sooner
- **Example**: Dating with apps (huge pool) vs small town (limited pool)

### 4. Multi-Armed Bandit
**Principle**: Balance exploring options vs exploiting best known.
- Each "arm" has unknown payoff distribution
- Pull arms to learn and earn
- Upper Confidence Bound: try uncertain options optimistically
- **Example**: A/B testing, restaurant choice, career paths

### 5. Explore/Exploit Trade-off
**Principle**: When to try new things vs stick with what works.
- More time remaining → explore more
- Less time remaining → exploit more
- Interval value: longer life expectancy = more exploration
- **Example**: Young: try many careers; Old: deepen expertise

### 6. Gittins Index
**Principle**: Assign each option a value considering future potential.
- Higher index = worth exploring
- Accounts for learning value, not just current estimate
- **Example**: Giving new restaurants "newcomer bonus" in decisions

---

## Sorting & Organization

### 7. Comparison Sorts
**Principle**: Different sorting strategies for different contexts.
- **Bubble sort**: Compare adjacent pairs (inefficient but simple)
- **Merge sort**: Divide, sort halves, merge (efficient, parallelizable)
- **Quick sort**: Pivot and partition (fast on average)
- **Example**: Ranking options by comparing pairs

### 8. Bucket Sort
**Principle**: Group into categories, then sort within.
- Works when you can categorize
- Reduces comparison load
- **Example**: Sort by "definitely yes," "maybe," "no," then rank within

### 9. Search Costs
**Principle**: Finding things has a cost that affects optimal organization.
- Frequently accessed → keep accessible
- Rarely used → store away
- Trade-off between filing (organizing) and searching (finding)
- **Example**: Email folders vs search, file organization

### 10. LRU Cache (Least Recently Used)
**Principle**: Keep recently used items accessible; discard oldest unused.
- Assumes recency predicts future use
- Automatically adapts to usage patterns
- **Example**: Browser tabs, desk organization, memory management

### 11. The Noguchi Filing System
**Principle**: Put most recent on top; always return to top.
- Self-organizing by recency
- No categorization needed
- Frequently used naturally floats up
- **Example**: Stack of papers where recent stays accessible

---

## Scheduling & Time

### 12. Earliest Due Date
**Principle**: Minimize maximum lateness by doing earliest deadline first.
- Optimal when all tasks same length
- Prevents worst-case delays
- **Example**: Multiple assignments with deadlines

### 13. Shortest Job First
**Principle**: Do quickest tasks first to minimize average wait time.
- Minimizes total time others wait
- Doesn't account for importance
- **Example**: Quick emails before long reports

### 14. Weighted Shortest Job First
**Principle**: Factor in importance, not just speed.
- Weight by importance/urgency
- High-priority short tasks first
- **Example**: Balance quick wins with important tasks

### 15. Priority Inversion
**Principle**: Low-priority tasks blocking high-priority ones.
- Medium priority preempts low, which blocks high
- Solution: priority inheritance
- **Example**: Urgent email delayed by low-priority meeting

### 16. Interrupt Coalescing
**Principle**: Batch interruptions to reduce context switch costs.
- Each interruption has overhead
- Check email once per hour, not continuously
- **Example**: Scheduled "office hours" instead of open door

### 17. Context Switching Costs
**Principle**: Changing tasks has hidden overhead.
- Loading mental context takes time
- Residue from previous task
- Minimize switches for deep work
- **Example**: Programming requires long uninterrupted blocks

### 18. Thrashing
**Principle**: System spends more time managing than working.
- Too many tasks → constant switching → nothing gets done
- Solution: reduce parallel tasks
- **Example**: Too many browser tabs, too many projects

---

## Optimization & Adaptation

### 19. Gradient Descent
**Principle**: Move in direction of steepest improvement.
- Local decisions toward better outcomes
- Can get stuck in local optima
- **Example**: Iterative product improvement based on feedback

### 20. Simulated Annealing
**Principle**: Accept worse solutions early to escape local optima.
- High "temperature" = more randomness, explore widely
- Low "temperature" = exploit, settle on solution
- **Example**: Try radical changes early in project, refine later

### 21. Hill Climbing
**Principle**: Always move to better adjacent state.
- Simple but can get stuck
- Good for smooth landscapes
- **Example**: A/B testing incremental improvements

### 22. Randomness in Optimization
**Principle**: Strategic randomness helps avoid getting stuck.
- Random restarts
- Jittering
- Monte Carlo methods
- **Example**: Try completely different approach when stuck

### 23. Relaxation
**Principle**: Solve easier version of problem, then constrain.
- Remove constraints to find approximate solution
- Add constraints back gradually
- **Example**: Ignore budget first, then adjust

### 24. Constraint Satisfaction
**Principle**: Find solution meeting all requirements.
- Propagate constraints to reduce possibilities
- Backtrack when stuck
- **Example**: Scheduling that meets everyone's availability

### 25. Lagrangian Relaxation
**Principle**: Turn constraints into costs.
- Soft constraints instead of hard
- Penalty for violation
- **Example**: "Budget is flexible but expensive to exceed"

---

## Quick Reference: Algorithm Selection

| Problem Type | Key Algorithms |
|--------------|----------------|
| When to commit | 37% Rule, Look-Then-Leap |
| Try new vs stay safe | Explore/Exploit, Multi-Armed Bandit |
| Organize and find | LRU Cache, Bucket Sort |
| Schedule tasks | Shortest Job, Earliest Due Date |
| Optimize gradually | Gradient Descent, Hill Climbing |
| Escape local optima | Simulated Annealing, Random Restarts |
| Handle too much | Interrupt Coalescing, Reduce Thrashing |
