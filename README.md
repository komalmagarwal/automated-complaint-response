# Automated Complaint Response Agent

An AI agent that automates responses to client complaints at a 
securities exchange, achieving 80% case deflection with no human 
intervention.

The agent identifies the client ID from incoming complaint 
communications, retrieves the relevant stock balance from the 
exchange's system, generates an accurate personalised response, 
and dispatches it — all autonomously. The remaining 20% of 
complex or edge-case complaints are routed to the human team.

## Impact
- 80% of complaints resolved automatically
- Faster response times for clients
- Human team freed for complex, high-judgement cases

## How it works
1. Parses incoming complaint for client identifier
2. Queries exchange system for live stock balance data
3. Generates personalised response using retrieved data
4. Routes unresolvable cases to human review queue

**Stack:** Python · NLP · API integration · Agentic workflow
