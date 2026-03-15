# Publish Gate (Enforced)

A page change is publish-ready only if all items are true:

1. **Taste score = 6/6** (see TASTE_SYSTEM.md)
2. **Tonight Test = pass** (see TONIGHT_TEST.md)
3. **Action artifact present** (plan/checklist/template/builder)
4. **Copy/paste script present**
5. **Best next tool present**
6. **Commit hash posted**
7. **GitHub Pages status = built**
8. **Live URL posted**

## Shipping report format (required)
- Commit: <hash>
- Changed: <files/pages>
- Why this is better for users: <1-3 bullets>
- Built status: built|failed
- Live URL: <url>
