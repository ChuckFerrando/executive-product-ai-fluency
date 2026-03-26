# Persistent AI Agent Workflows

## Pattern Definition

Using continuously running AI agents to automate recurring workflows without manual intervention.

## Core Idea

Instead of executing tasks manually or via prompts, define workflows that run automatically through persistent agents.

## When to Use

- Recurring tasks
- Monitoring tasks
- Multi-step workflows
- Time-based automation

## Example Use Cases

### 1. Standup Automation
- Scan Slack channels
- Identify blockers
- Generate summary
- Post to team channel

### 2. Competitive Monitoring
- Visit competitor sites regularly
- track changes
- generate reports

### 3. Bug Routing
- ingest bug reports
- classify by customer tier
- route automatically

## Implementation Structure

1. Define objective
2. Assign agent
3. Set trigger (time/event)
4. Define output format
5. Monitor + refine

## Key Design Principles

- Start with one workflow
- Validate before scaling
- Use specialized agents per task
- Maintain control layers

## Failure Modes

- Over-automation too early
- poor permission control
- lack of monitoring
- unclear objectives

## Skill Development

To master this pattern:
- learn workflow decomposition
- understand system boundaries
- design for control and safety

## Outcome

Shifts work from:

manual execution → system-level delegation
