# Lab-M6.03-Build-Dashboard-for-Web-Tier-Health

# Lab M6.03 - Build Dashboard for Web Tier Health

## Dashboard Design Rationale
Describe why you organized the dashboard the way you did (e.g., Golden Signals
at the top for quick triage, resource utilization below, correlation at the bottom).

## Widget Explanations
| Widget | Type | Purpose |
|--------|------|---------|
| Request Rate | Time Series | Shows traffic volume over time |
| Error Rate | Single Value | Highlights current 5XX percentage |
| P95 Latency | Time Series | Tracks user-facing response time |
| ... | ... | ... |

## How to Use This Dashboard
1. Start at the top row — single-value widgets show current state
2. Scroll to Golden Signals for trends over the last 3 hours
3. Check EC2 resources if Golden Signals are elevated
4. Use the Correlation view to identify root cause patterns

## Screenshots
- `screenshots/01-full-dashboard.png`
- `screenshots/02-golden-signals.png`
- `screenshots/03-resource-utilization.png`
- `screenshots/04-correlation-view.png`
