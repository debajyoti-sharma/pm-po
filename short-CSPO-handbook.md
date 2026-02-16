# CSPO Handbook – Condensed (~10 pages)

---

## Customer-centric product foundations

### Product principles
A product should:
1. Be customer centric
2. Solve a real problem / fulfill a real need
3. Be useful AND usable
4. Involve customers regularly for early feedback
5. Keep cost of change under control via early learning
6. Leverage relevant technology
7. Have a clear vision and strong strategy
8. Have an empowered Product Owner accountable for end-to-end value

### Focus on NEED, not REQUIREMENT (example)
Customer says: “I need a wheelchair.”
Underlying need: comfort + mobility for an elderly person recovering from surgery.

### Usefulness vs Usability
A product may be useful but not usable. Product Owners must keep validating user experience.

---

## Product levels

Product levels:
- Generic: basic version fulfilling the need
- Expected: features users expect
- Augmented: features beyond expectations
- Potential: future features users may expect

**Example (Mobile):** Core benefit is communication.

`![Product Levels Pyramid](cspo_product_levels_pyramid.png)`

---

## Product lifecycle & mindset

### Product lifecycle
Idea → Creation → Introduction → Growth → Maturity → Retirement

`![Product Lifecycle](cspo_product_lifecycle.png)`

### Project vs Product
| Project | Product |
|---|---|
| Temporary | Permanent/ongoing |
| Built for one customer | Built for market segments |
| One-off delivery | Continuous improvements |
| Predictive planning | Adaptive planning |
| Short-lived project teams | Long-lived feature teams |
| Fixed requirements | Evolving customer needs |

---

## MVP & iterative delivery

### Minimum Viable Product (MVP)
An MVP is the smallest version that enables maximum validated learning with least effort.

Key idea: observe what users actually do, not what they say they would do.

**Examples included in handout:**
- Airbnb: started with air beds + simple webpage, validated demand, then scaled.
- Spotify: launched a desktop app with only streaming, then expanded and monetized.

### Big-bang vs iterative & incremental
Iterative + incremental delivery enables earlier feedback and lower risk.

---

## Agile & Scrum foundations

### What is agility?
- Frequent delivery → early feedback
- Consistent delivery → increased ROI

### Agile Manifesto (summary)
Values:
- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change over following a plan

Principles (themes):
- Early and continuous delivery
- Welcome change
- Frequent working increments
- Close collaboration
- Sustainable pace
- Working software as primary measure
- Continuous improvement

### Scrum overview
Scrum is a framework for complex problems using empiricism:
- Transparency
- Inspection
- Adaptation

---

## Scrum framework essentials

### Scrum Team
- Product Owner
- Developers
- Scrum Master
Team size typically 10 or fewer.

### Sprint
- Timeboxed, max 1 month (or less)
- Container event containing:
  - Sprint Planning
  - Daily Scrum
  - Sprint Review
  - Sprint Retrospective
- Product Backlog Refinement is ongoing during the Sprint.

Sprint cancellation:
- Only Product Owner can cancel
- Only when Sprint Goal becomes obsolete

### Scrum artifacts & commitments
Artifacts enhance transparency and represent work/value:
- Product Backlog → commitment: Product Goal
- Sprint Backlog → commitment: Sprint Goal
- Increment → commitment: Definition of Done

---

## Product Owner role (core accountability + decisions)

Product Owner is one person (not committee). Primary accountability: maximize product value.

PO is accountable for:
- Developing and communicating Product Vision and Product Goal
- Creating Product Backlog items
- Ordering Product Backlog items
- Ensuring backlog transparency

PO decisions include:
- Backlog content
- Backlog ordering
- Accept/reject work
- When to release increment
- When to cancel a Sprint

PO focus:
- Why + What (not How)
- Encourage direct developer–stakeholder interaction (not act as proxy)

PO in the Sprint (high level):
- Planning: explain items, align Sprint Goal, clarify, trade-offs
- Development: clarify/verify/approve done items
- Review: explain done/not done, gather feedback, update forecast
- Retrospective: receive/give improvement inputs
- Refinement: collaborate; involve devs for estimates

---

## Product discovery & user research

Product discovery helps identify ideas that are useful and usable.

User vs Customer:
- User: uses without paying
- Customer: pays to use

User research:
- Validates assumptions/hypotheses
- Provides qualitative insight into needs/behaviors
- Improves design iteratively

Common methods:
- A/B testing
- Contextual inquiry
- Focus groups
- Heatmaps
- Interviews
- Prototypes
- Surveys
- User feedback

---

## Persona (example graphic retained)

`![Persona Canvas](cspo_persona_canvas.png)`

---

## Value Proposition Canvas (example graphic retained)

Value Proposition Canvas:
Customer Profile:
- Jobs
- Pains
- Gains

Value Map:
- Products & services
- Pain relievers
- Gain creators

Fit = value proposition addresses most significant pains and gains.

`![Value Proposition Canvas](cspo_value_proposition_canvas.png)`

---

## Product vision (examples + graphics retained)

Vision clarifies:
- Why build the product?
- Who is it for?
- What problem/need does it address?
- Desired end state
- Differentiators / success factors

Good vision is:
- Big
- Inspiring
- Concise
- Shared & stable

Techniques:
- Elevator statement
- Vision board/poster
- One pager
- Press release

Elevator statement format:
FOR <target>
WHO <need>
THE <product> IS A <category>
THAT <key benefit>
UNLIKE <alternative>
OUR PRODUCT <differentiator>

`![Product Vision Board](cspo_product_vision_board.png)`

---

## Product backlog, prioritization, stories, DoD, increments, release planning

### Product Roadmap
Steps:
1. Gather inputs (audience, tech, market, backlog)
2. Organize by timespan
3. Visualize coarse-grained features per release
4. Get buy-in from stakeholders + team

### Prioritization
Business value is key.
Techniques:
- Dot voting
- MoSCoW
- Urgency vs importance
- Value vs cost
- ROI / break-even analysis

Ordering heuristic:
(Order Rank) = (Business Value + Risk) / Cost

Example:
- Save: (5 + 0) / 1 = 5
- Print: (4 + 1) / 2 = 2.5

### Product backlog
- Ordered list of all work
- Higher-order items are more detailed
- One product backlog even with multiple teams

### User stories
3Cs: Card, Conversation, Confirmation

Format:
As a <user>, I want <capability> so that <value>.

Acceptance criteria example (Visa payment):
- Only Visa accepted; others rejected with message
- Valid digits, valid CVV (3 digits)
- Expired cards rejected
- Success confirmation via email/SMS
- Errors & failures handled with clear messaging

Good acceptance criteria: SAFE
- Success
- Advance
- Failure
- Error

INVEST user story qualities:
- Independent, Negotiable, Valuable, Estimable, Small, Testable

### Increment
- Collection of done PBIs meeting DoD
- Must be usable regardless of release choice
- Multiple increments can exist per Sprint

### Definition of Done (DoD)
- Quality checklist
- Commitment for increment
- Owned by developers
- Different per product but shared across teams when multiple teams exist

DoD vs Acceptance Criteria:
- AC = functionality, story-specific, PO-owned
- DoD = quality, increment-wide, dev-owned

### Release planning (not core Scrum)
Prereqs:
- Prioritized + estimated backlog
- Velocity range
- Conditions of satisfaction

Two modes:
- Fixed scope (feature-driven): estimate sprints using velocity range
- Fixed date (date-driven): determine will-have vs might-have lines

Tracking:
- Sprint burndown (dev-owned)
- Release burnup/burndown (PO updates end of each sprint)
