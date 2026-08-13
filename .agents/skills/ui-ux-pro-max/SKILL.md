---
name: ui-ux-pro-max
description: UI/UX design intelligence for Codex. Use for interface design, accessibility, responsive layouts, typography, colors, animation, components, and UX review.
---

# UI/UX Pro Max for Codex

Use the existing UI/UX Pro Max resources in this repository.

## Search

Run from the repository root:

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "<query>" --domain <domain>
```

For a new page or project:

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "<product> <industry> <keywords>" --design-system -p "Project Name"
```

For stack-specific guidance:

```bash
python3 .claude/skills/ui-ux-pro-max/scripts/search.py "<keyword>" --stack <stack>
```

## Priorities

1. Accessibility
2. Interaction
3. Performance
4. Visual consistency
5. Responsive layout
6. Typography and color
7. Meaningful motion
8. Forms and feedback
9. Navigation
10. Data visualization

## References

Use:
- `.claude/skills/ui-ux-pro-max/references/quick-reference.md`
- `.claude/skills/ui-ux-pro-max/references/pro-rules.md`

Never fabricate database results. If a search returns no result, broaden the query once, then use general UI/UX best practices.
