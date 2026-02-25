# Risk Models

Mental models for uncertainty, fragility, and tail events. Heavily influenced by Nassim Taleb's work.

## Contents
- [Uncertainty & Probability](#uncertainty--probability)
- [Fragility Spectrum](#fragility-spectrum)
- [Tail Risk & Black Swans](#tail-risk--black-swans)
- [Risk Management](#risk-management)

---

## Uncertainty & Probability

### 1. Risk vs Uncertainty (Knight)
**Principle**: Distinguish calculable risk from unmeasurable uncertainty.
- **Risk**: Known probability distribution (dice, cards)
- **Uncertainty**: Unknown unknowns (novel situations)
- Most important decisions involve uncertainty, not risk
- **Example**: Insurance (risk) vs startup (uncertainty)

### 2. Aleatory vs Epistemic Uncertainty
**Principle**: Irreducible randomness vs reducible ignorance.
- **Aleatory**: Inherent randomness (quantum mechanics, dice)
- **Epistemic**: Could know but don't (hidden information)
- Different strategies for each
- **Example**: Weather (aleatory) vs competitor plans (epistemic)

### 3. Known Knowns Matrix (Rumsfeld)
**Principle**: Four quadrants of knowledge.
- Known knowns: What we know we know
- Known unknowns: What we know we don't know
- Unknown knowns: Tacit knowledge
- Unknown unknowns: What we don't know we don't know
- **Example**: The dangerous quadrant is unknown unknowns

### 4. Calibrated Uncertainty
**Principle**: Confidence should match accuracy.
- 90% confidence should be right 90% of the time
- Most people are overconfident
- Trainable through feedback
- **Example**: Use wide confidence intervals until calibrated

### 5. Ergodicity
**Principle**: Time average may differ from ensemble average.
- Ensemble: average across many people at one time
- Time: one person's average over time
- Russian roulette: good ensemble average, bad time average
- **Example**: Repeated gambles where ruin is possible

---

## Fragility Spectrum

### 6. Fragile
**Principle**: Harmed by volatility, randomness, and stressors.
- Prefers calm, predictable environments
- Breaks under stress
- **Examples**: Porcelain, highly leveraged positions, overoptimized systems

### 7. Robust
**Principle**: Resists volatility; neither helped nor harmed.
- Survives stress unchanged
- Defensive posture
- **Examples**: Stone, diversified portfolio, redundant systems

### 8. Antifragile (Taleb)
**Principle**: Gains from disorder, volatility, and stressors.
- Gets stronger under stress (up to a point)
- Thrives in uncertainty
- **Examples**: Muscles (from exercise), evolution, small failures building immunity
- **Key insight**: Some things need randomness to thrive

### 9. Hormesis
**Principle**: Small doses of harm are beneficial.
- Vaccines, exercise, fasting
- Dose matters: too much is toxic
- **Example**: Cold showers, intermittent fasting

### 10. Via Negativa
**Principle**: Improve by removing, not adding.
- Less is more
- Remove fragilities rather than add features
- **Example**: Health through not smoking > health through supplements

---

## Tail Risk & Black Swans

### 11. Black Swans
**Principle**: Rare, high-impact events that are unpredictable but retrospectively "obvious."
- Not in the model until they happen
- Carry most of the impact in certain domains
- **Example**: 2008 financial crisis, COVID-19, internet

### 12. Fat Tails vs Thin Tails
**Principle**: How extreme are the extremes?
- **Thin tails** (Gaussian): Extremes are limited (height, weight)
- **Fat tails** (Power law): Extremes dominate (wealth, book sales, casualties)
- Don't use thin-tail statistics for fat-tail phenomena
- **Example**: Average book sales meaningless; bestsellers dominate

### 13. Ludic Fallacy
**Principle**: Confusing real-world uncertainty with game-like risk.
- Games have known rules and probabilities
- Real world has unknown unknowns
- **Example**: Treating market risk like casino risk

### 14. Turkey Problem
**Principle**: Past performance doesn't predict paradigm shifts.
- Turkey fed 1000 days → "evidence" of safety → day 1001 is Thanksgiving
- Model built on past data misses structural breaks
- **Example**: Banks "safe" until 2008

### 15. Extremistan vs Mediocristan
**Principle**: Domains where extremes dominate vs where they don't.
- **Mediocristan**: Physical quantities, normal distribution, average matters
- **Extremistan**: Information, wealth, winner-take-all, average meaningless
- **Example**: Height (Mediocristan) vs wealth (Extremistan)

### 16. Precautionary Principle
**Principle**: For irreversible, systemic risks, act despite uncertainty.
- When stakes are ruin, evidence standards differ
- Burden of proof on those creating risk
- **Example**: Nuclear weapons, GMOs in ecosystem, AI safety

---

## Risk Management

### 17. Margin of Safety
**Principle**: Build buffers between estimates and requirements.
- Engineers: design for 2x expected load
- Investors: buy at discount to estimated value
- **Example**: Bridge rated for 10 tons, trucks limited to 5

### 18. Barbell Strategy
**Principle**: Combine very safe with very speculative; avoid middle.
- 90% in ultra-safe (cash, treasuries)
- 10% in high-risk/high-reward (startups, options)
- Middle-risk has hidden fragility
- **Example**: Career: stable income + side ventures

### 19. Redundancy
**Principle**: Duplicate critical components.
- Backup systems, multiple suppliers
- Costly in normal times, invaluable in crisis
- Nature uses redundancy extensively
- **Example**: Two kidneys, multiple power sources

### 20. Position Sizing
**Principle**: Never bet so much that ruin is possible.
- Survival first, optimization second
- Kelly criterion: optimal bet size = edge / odds
- Be more conservative than Kelly suggests
- **Example**: Never invest money you can't afford to lose

### 21. Asymmetric Payoffs
**Principle**: Seek situations where upside >> downside.
- Limited downside, unlimited upside
- Option-like payoffs
- **Example**: Buying options (lose premium max, unlimited gain)

### 22. Skin in the Game
**Principle**: Decision-makers should bear consequences.
- Aligns incentives
- Filters out empty talk
- **Example**: Surgeons shouldn't just recommend; investors should own stock

### 23. Small Bets
**Principle**: Many small experiments beat few large ones.
- Learn from failures without ruin
- Optionality: can scale winners
- **Example**: Venture portfolio, product experiments

### 24. Reversibility Premium
**Principle**: Pay more for reversible decisions.
- Irreversible decisions need higher confidence
- Two-way doors: decide quickly, iterate
- One-way doors: proceed carefully
- **Example**: Renting vs buying, dating vs marriage

### 25. Correlation in Crisis
**Principle**: Assets become correlated during stress.
- Diversification works in normal times
- Everything sells together in crisis
- Need truly uncorrelated hedges
- **Example**: 2008: all "diversified" assets fell together

---

## Quick Reference: Risk Framework

| Domain | Key Models |
|--------|------------|
| Understanding risk type | Risk vs Uncertainty, Thin vs Fat Tails |
| Building resilience | Antifragility, Redundancy, Margin of Safety |
| Portfolio construction | Barbell, Position Sizing, Small Bets |
| Black Swan preparation | Turkey Problem, Precautionary Principle |
| Aligning incentives | Skin in the Game, Asymmetric Payoffs |
| Navigating uncertainty | Via Negativa, Reversibility Premium |
