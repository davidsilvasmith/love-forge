# Publish Gate (Enforced)

A page change is publish-ready only if all items are true:

1. **Taste score = 6/6** (see TASTE_SYSTEM.md)
2. **Tonight Test = pass** (see TONIGHT_TEST.md)
3. **Action artifact present** (plan/checklist/template/builder)
4. **Copy/paste script present**
5. **Best next tool present**
6. **Multi-issue clarity present** (if users likely have multiple simultaneous issues, page must explicitly tell them how to pick one focus tonight)
7. **Commit hash posted**
8. **GitHub Pages status = built**
9. **Live URL posted**

## Shipping report format (required)
- Commit: <hash>
- Changed: <files/pages>
- Why this is better for users: <1-3 bullets>
- Built status: built|failed
- Live URL: <url>
