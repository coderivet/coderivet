## coderivet

Frontend engineer working on long-lived Ember applications - the kind where Classic and Octane patterns coexist, migration debt has to be paid down without stopping delivery, and the bugs that matter most are often the ones the linter misses entirely.

I write about what I actually encounter: collision patterns at architectural boundaries, decision frameworks for mixed-pattern code, safer upgrade paths, and deliberate AI collaboration when the codebase is real and the pressure is production.

---

### Writing - [dev.to/coderivet](https://dev.to/coderivet)

**Navigating Ember's Mixed-Pattern Codebases** - four-part series

- **What Your Linter Doesn't See: Mixed-Pattern Collisions in Ember Codebases** - Article 1 *(coming soon)*
- Convert, Wrap, or Leave? A Decision Framework for Mixed-Pattern Ember Code - Article 2 *(coming soon)*
- Making Ember Upgrades Safer: Codemods, Deprecations, and Tracking - Article 3 *(coming soon)*
- PR Review as Risk Analysis: When AI Reads Your Ember Diffs - Article 4 *(coming soon)*

---

### Artifacts - ember-ai-workflow

Companion repository for the series *(coming soon)*. Three layers:

- **Collision Catalog** - 14 named patterns with severity, boundary, detection status, and safe fix guidance
- **Scanner** - static analysis for collision candidates. Zero dependencies. Runs on Node.js against your actual codebase.
- **Playground** - synthetic fixtures to see the scanner output before pointing it at anything real

---

### On AI in this work

I use AI as a structured collaborator: code review, context retention, and pattern recognition across a codebase too large to hold in working memory at once.

Not as a substitute for engineering judgment. The final call is always mine.

The series is partly about what that workflow actually looks like - and where the boundary is.

---

*Rivets hold things together at the joint where the pressure is highest.*
