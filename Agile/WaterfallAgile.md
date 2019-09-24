## Waterfall Method 💧

Traditional approach to Software Development. Captures requirements and then cascades each key deliverable through series of different stages:

- **Requirement Analysis** - understand what the client wants from the software.
- **Design** - Build out a project plan and outlines the scope of work.

- **Development** - Code the application as per plan and design.

- **Testing** - Ensure applications meet the requirements.

- **Maintenance** - Ensure applications keeps working. Address any security risks.

**Disadvantages**

- Difficult to integrate any new requirements without needing to restart programme.

- Spending weeks/months away from client can lead to dissatisfaction with end product.

## Agile Model 🐿

**Benefits**

- Allows Developers to create prototypes and get those to the client with the requirements faster.

- Client is able to send requirements back. Creates a feedback loop.

- Engagement cycle is usually 2 weeks (sprints).

- Each feedback loop has:
  - Planning
  - Coding
  - Testing
  - Review

Every 2 weeks, client can provide feedback at end of each sprint.

Workflow of Agile model:

- **Product Backlog** - bunch of features (small or large) bug fixes
- **Sprint Planning** - break out the work (mixture of small, medium and large solutions)
- **Sprint backlog**
- **Sprint** - 2 weeks, with a daily scrum (Plan, code, test, review) Any blockers? Ensure those blockers are being addressed so everybody stays on track
- **Deliverable product** (at end of 2 weeks)
- **Product review with client**

Client requirements are better understood because they're integrated with the scrum team. The product is delivered faster with a review of implemented Features at the end of each sprint.

**Disadvantages**

- The product gets tested only on developer computers, not on production systems (difficult to mimic).
- Developers and Ops team running in silos. Devs run sprints and building features. Then passed to Ops team. Their job to install software and ensure environment is stable.
- If product fails in production servers (setup configuration, missing dependency, link to API etc), the ops team are clueless and send product back to dev team.

This is where [DevOps](./Agile/DevOps) comes in..
