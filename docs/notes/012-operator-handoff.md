# Operator Handoff

Domain: healthcare analytics

This note records an implementation detail for Care Gap Prioritizer. The current operating
threshold is `0.45` and review should happen within `48` hours
for records above that level.

## Checks

- confirm input fields are present
- verify score ordering is stable
- compare high exposure records against the review queue
