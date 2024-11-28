
# Building Three Apps with n8n

## Overview
This assignment involves building three apps using the n8n platform (free quota):

### a) Chat Frontend App
- A customer support chat app.
- Features:
  - Handles user queries via a chat .
  - Uses an AI agent for responses.
  - Escalates unresolved queries to human agents.
- [Video Demo ](https://youtu.be/3l6XOI1wArY)

### b) Backend Triggered App
- An app triggered by backend events like Kafka or emails.
- Features:
  - Automates workflows for event-based triggers.
  - Sends backend-triggered emails.
- [Video Demo ]()
  
### c) Human-in-the-Loop App
- An app that involves human intervention when AI fails.
- Features:
  - AI-powered responses.
  - Escalates to human agents for unresolved queries.
  - Reference Workflow: [Ask a Human for Help](https://n8n.io/workflows/2095-ask-a-human-for-help-when-the-ai-doesnt-know-the-answer).
- - [Video Demo ]()

## Steps
1. **Set Up n8n**: Self-host or use the free n8n cloud service.
2. **Build Workflows**:
   - Chat App: Use Webhook and AI Agent nodes.
   - Backend App: Use Kafka Trigger and Email nodes.
   - Human-in-the-Loop: Use escalation workflows.
3. **Test and Deploy**: Validate workflows and ensure deployment readiness.

## Resources
- [n8n Docs](https://docs.n8n.io/)
- [Workflow Templates](https://n8n.io/workflows)
- [Self-Hosting Guide](https://n8n.io/blog/self-host-n8n-with-docker/)

---

### Notes
- Use the free n8n quota for testing.
- Submit workflows with this README for evaluation.
