# Transaction Tracing Playbook

## Objective

Build a defensible chain-of-events record for a suspicious asset movement.

## Inputs

- Starting wallet address
- Known transaction hashes
- Chain/network
- Token contracts
- Approximate incident time
- Public reports or user-provided evidence

## Workflow

1. Confirm the starting transaction and network.
2. Identify direct outgoing transfers.
3. Group follow-on addresses by transaction behavior, timing, and token movement.
4. Record bridge, swap, mixer, exchange, or contract interactions as labels only when evidence supports them.
5. Maintain a timeline with UTC timestamps.
6. Preserve links to explorers and official sources.

## Output

- Timeline
- Address table
- Transaction table
- Known labels and confidence levels
- Recommended escalation package
