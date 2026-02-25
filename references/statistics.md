# Statistical Models

Mental models for interpreting data, probability, and making predictions. Draws from Nate Silver's "The Signal and the Noise" and statistical foundations.

## Contents
- [Probability Foundations](#probability-foundations)
- [Distributions & Patterns](#distributions--patterns)
- [Prediction & Inference](#prediction--inference)
- [Common Pitfalls](#common-pitfalls)

---

## Probability Foundations

### 1. Bayes' Theorem
**Principle**: Update beliefs based on new evidence.
- P(A|B) = P(B|A) × P(A) / P(B)
- Prior × Likelihood / Evidence = Posterior
- **Key insight**: Prior probability matters enormously
- **Example**: Positive rare disease test → still likely healthy if disease is rare

**Practical form**:
- Prior odds × Likelihood ratio = Posterior odds
- Start with base rate, update with evidence strength

### 2. Base Rates
**Principle**: The frequency in the general population.
- Always ask: "How common is this typically?"
- Specific evidence must be weighted against base rates
- **Example**: Most CEOs are tall, but most tall people aren't CEOs

### 3. Conditional Probability
**Principle**: P(A given B) differs from P(B given A).
- P(rain|clouds) ≠ P(clouds|rain)
- Classic confusion in medical diagnosis
- **Example**: P(symptoms|disease) vs P(disease|symptoms)

### 4. Independence
**Principle**: Events that don't influence each other.
- P(A and B) = P(A) × P(B) only if independent
- True independence is rare; don't assume it
- **Example**: Coin flips independent; stock returns often not

### 5. Law of Large Numbers
**Principle**: Average approaches expected value with more trials.
- Short run: anything can happen
- Long run: statistics win
- **Example**: Casino always wins given enough bets

### 6. Expected Value
**Principle**: Probability-weighted average of outcomes.
- EV = Σ(P_i × V_i)
- Positive EV bets should be taken repeatedly
- **Example**: EV of dice roll = (1+2+3+4+5+6)/6 = 3.5

---

## Distributions & Patterns

### 7. Normal Distribution (Gaussian)
**Principle**: Bell curve describes many natural phenomena.
- Mean, median, mode coincide
- 68-95-99.7 rule (within 1, 2, 3 standard deviations)
- **Applies to**: Height, test scores, measurement errors
- **Example**: Most people near average height; extremes rare

### 8. Power Laws (Pareto)
**Principle**: Few items dominate; long tail of small items.
- 80/20 rule: 20% of causes → 80% of effects
- No meaningful "average"
- **Applies to**: Wealth, city sizes, word frequency, website traffic
- **Example**: Top 1% of videos get majority of views

### 9. Fat Tails
**Principle**: Extreme events more common than normal distribution predicts.
- Black swans lurk in the tails
- Don't use normal distribution for financial returns
- **Example**: Market crashes happen far more often than bell curve predicts

### 10. Regression to the Mean
**Principle**: Extreme observations tend to be followed by less extreme ones.
- Not causation; it's statistical artifact
- First measurement includes luck; second measurement less lucky
- **Example**: Rookie of the Year often has sophomore slump

### 11. Simpson's Paradox
**Principle**: Aggregate trends can reverse when data is disaggregated.
- Group A beats Group B overall, but B beats A in every subgroup
- Hidden third variable explains reversal
- **Example**: Hospital with worse overall survival has better rates for each disease severity

### 12. Survivorship Bias
**Principle**: We only see what survived; failures are invisible.
- Successful entrepreneurs studied; failures forgotten
- Mutual fund performance overstated (dead funds excluded)
- **Example**: "Buildings were built better in the past" – no, bad ones fell down

---

## Prediction & Inference

### 13. Signal vs Noise
**Principle**: Distinguish meaningful patterns from random variation.
- More data doesn't help if it's all noise
- Overfit to noise = poor prediction
- **Example**: Stock tips based on patterns that are just randomness

### 14. Confidence Intervals
**Principle**: Range of plausible values, not point estimates.
- 95% CI means 95 of 100 such intervals contain true value
- Wide interval = more uncertainty
- **Example**: "Between 40% and 60%" more honest than "50%"

### 15. Correlation vs Causation
**Principle**: Correlation doesn't imply causation.
- A could cause B, B could cause A, or C could cause both
- Need controlled experiments or careful inference
- **Example**: Ice cream sales correlate with drowning (both caused by summer)

### 16. Selection Bias
**Principle**: Non-random sampling distorts conclusions.
- Who chose to participate? Who dropped out?
- **Example**: Survey only reaches those who answer phones

### 17. Overfitting
**Principle**: Model explains noise, not just signal.
- Great fit on training data; poor on new data
- More parameters = more overfitting risk
- **Example**: Model predicting Super Bowl winner from NFC/AFC pattern

### 18. Sample Size Effects
**Principle**: Small samples have high variance.
- Extreme results more likely from small groups
- Don't over-interpret small samples
- **Example**: Small hospitals have highest AND lowest mortality rates

### 19. Multiple Comparisons Problem
**Principle**: Testing many hypotheses → some will be "significant" by chance.
- Test 20 things at 5% significance → expect 1 false positive
- Requires correction (Bonferroni, etc.)
- **Example**: One food linked to cancer when testing hundreds

---

## Common Pitfalls

### 20. Gambler's Fallacy
**Principle**: Believing past random events affect future probabilities.
- "It's due for heads" after streak of tails
- Each flip is independent
- **Example**: Roulette wheel has no memory

### 21. Hot Hand Fallacy
**Principle**: Believing performance streaks predict future performance.
- Sometimes real (skill), sometimes illusion (luck)
- Hard to distinguish without large samples
- **Example**: Shooter "on fire" may just be within normal variance

### 22. Neglect of Probability
**Principle**: Treating unlikely events as impossible (or certain).
- 1% risk ≠ 0%; 99% ≠ 100%
- Matters enormously for rare, high-impact events
- **Example**: "That will never happen" → then it does

### 23. Conjunction Fallacy
**Principle**: Specific scenarios seem more likely than general ones.
- P(A and B) ≤ P(A)
- Stories feel more probable than statistics
- **Example**: "Bank teller and feminist" seems more likely than "bank teller"

### 24. Denominator Neglect
**Principle**: Focusing on numerator, ignoring base.
- "10 deaths" sounds worse than "10 in 10 million"
- Always ask: out of how many?
- **Example**: Rare disease seems common when cases reported without context

### 25. Availability Heuristic
**Principle**: Judging frequency by ease of recall.
- Dramatic events overweighted (plane crashes vs car accidents)
- Recent events overweighted
- **Example**: Fear of terrorism > fear of heart disease

---

## Quick Reference: When to Use Each Model

| Situation | Key Models |
|-----------|------------|
| Updating beliefs with evidence | Bayes' Theorem, Base Rates |
| Analyzing extreme values | Fat Tails, Power Laws |
| Predicting future from past | Regression to Mean, Signal vs Noise |
| Evaluating research claims | Sample Size, Selection Bias, Multiple Comparisons |
| Understanding distributions | Normal vs Power Law, Survivorship Bias |
| Assessing risk | Expected Value, Neglect of Probability |
