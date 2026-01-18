# Philosophy on Engineering

## Core Principles

### Code is Communication
Code is read more than it's written. Optimize for readability and maintainability, not cleverness. Future you (and your teammates) will thank you.

### Simplicity Wins
The best code is no code. The second best is simple code. Complexity should be justified by proportional value.

### Abstractions Have Costs
Every abstraction is a trade-off. Good abstractions hide complexity and expose clarity. Bad abstractions just move complexity around while adding cognitive overhead.

### Tests Enable Speed
Tests feel like they slow you down, but they enable confident refactoring and fast iteration. Untested code becomes code you're afraid to change.

## On Technical Decisions

### Boring Technology is Good
Use proven, well-understood technology when possible. Save your innovation tokens for problems that are core to your business. New and shiny is rarely better.

### Make Decisions Reversible
When you can, structure decisions to be easily reversible. When you can't, invest more in getting them right upfront. Know the difference.

### Optimize Later
Premature optimization wastes effort on problems that may not matter. Measure first, then optimize the actual bottlenecks. Your intuition about performance is probably wrong.

### Documentation is Investment
Good documentation pays dividends over time. It enables onboarding, reduces interruptions, and forces clarity of thought. Write docs for future strangers.

## On Technical Leadership

### Leaders Write Code
Technical leaders who don't write code lose touch with reality. Stay close to the codebase, even if you can't be in it full-time.

### Create Context, Not Control
Your job is to create the context in which good decisions happen, not to make all the decisions yourself. Share information, clarify goals, trust your team.

### Technical Debt is a Conversation
Tech debt isn't inherently bad - it's a trade-off. The failure is not having explicit conversations about it. Make the trade-offs visible and intentional.

### Review is Teaching
Code review is primarily a teaching and learning opportunity, secondarily a quality gate. Invest in making reviews constructive and educational.

## On Systems Thinking

### Everything is a System
Code exists in a system of users, infrastructure, business constraints, and team dynamics. Technical decisions that ignore the system will fail.

### Feedback Loops Matter
Build systems with tight feedback loops. Fast iteration beats perfect planning. Monitoring, alerting, and observability are features, not overhead.

### Design for Failure
Everything fails. Design systems that degrade gracefully, recover automatically, and fail in predictable ways. Hope is not a strategy.

### Second-Order Effects
Technical decisions have cascading consequences. The choice of database affects hiring, operations, costs, and feature velocity. Think through implications.

## On Career

### Breadth and Depth
T-shaped skills serve you well. Deep expertise in something, broad familiarity with many things. Both matter at different times.

### Writing is Thinking
Engineers who write well think well. Technical writing is a leverage skill that multiplies your impact.

### Learn from Production
The most valuable learning comes from operating systems in production. Embrace on-call, incident response, and debugging. Theory is no substitute for experience.

### Mentorship Matters
Invest in mentoring others. Teaching deepens your own understanding and builds your network. The industry is small - relationships compound.

## On Process

### Process Should Enable
Process exists to help people do better work, not to control them. If process feels like overhead, it's probably wrong.

### Iteration Over Planning
Long planning cycles produce stale plans. Prefer short iterations with frequent adjustment. Plans are useless, but planning is essential.

### Meetings Have Costs
Every meeting has an opportunity cost. Be ruthless about whether a meeting is the right format. Many meetings should be documents.

### Async by Default
Asynchronous communication respects people's time and attention. Default to async, escalate to sync when needed.
