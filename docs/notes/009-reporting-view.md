# Reporting View

Domain: healthcare analytics

This note records an implementation detail for Care Gap Prioritizer. The current operating
threshold is `0.8` and review should happen within `72` hours
for records above that level.

## Checks

- confirm input fields are present
- verify score ordering is stable
- compare high exposure records against the review queue
