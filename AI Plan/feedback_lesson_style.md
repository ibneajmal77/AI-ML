---
name: Lesson Teaching Style — Production Perspective
description: All lessons must be written from the perspective of someone with production ML experience — include real deployment patterns, gotchas, monitoring, drift, and decision frameworks
type: feedback
---

User explicitly requested that lessons be enhanced with production experience perspective and include production-related content.

**Why:** Senior FSE with 8 years production experience. Textbook-only lessons are not enough — needs to know how things work when deployed, what breaks, and how to make real decisions.

**How to apply:**
- Every lesson notebook must include at least one "PRODUCTION REALITY" section
- Include concept drift, monitoring, retraining patterns where relevant
- Add a production decision framework or gotcha section
- Use existing background (Kafka, K8s, Azure, microservices) as production analogies
- Show the gap between "textbook ML" and "deployed ML" explicitly
- Avoid toy-only examples — always connect code to a real production use case
