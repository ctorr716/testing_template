# PR Title: <short + specific>

## Summary
<!-- 2-4 sentences: what is this PR and why does it exist? -->

## Trust Factor (0–10)
**Trust Factor:** _/10  
**Why:** <!-- ex: “small change, covered by tests, feature flag, manual verification” -->

---

## What Changed
Check all that apply and describe briefly.

### UI
- [ ] No UI changes
- [ ] UI changes
**Details:**  
- <!-- ex: “Updated Profile page layout, added loading skeleton, fixed button states.” -->

### API / Backend
- [ ] No backend changes
- [ ] Backend changes
**Details:**  
- <!-- ex: “Added endpoint GET /students/{id}/visits; updated validation.” -->

### DB
- [ ] No DB changes
- [ ] DB schema changes (migration)
- [ ] DB data changes (seed/backfill)
**Details:**  
- <!-- ex: “Added Visits table + index on (student_id, visit_date). Migration: 2026_02_16_add_visits.sql” -->

### Integrations / External Services
- [ ] None
- [ ] Added/changed integrations
**Details:**  
- <!-- ex: “Updated Twilio callback handler; new env var TWILIO_WEBHOOK_SECRET.” -->

### Infra / DevOps
- [ ] None
- [ ] CI/CD, Docker, hosting changes
**Details:**  
- <!-- ex: “New GitHub Action step to run integration tests; bumped dotnet SDK.” -->

### Docs
- [ ] None
- [ ] Updated docs
**Details:**  
- <!-- ex: “Updated README setup steps + API examples.” -->

---

## Screenshots / Demo
- **Before:** <!-- link or image -->
- **After:** <!-- link or image -->
- **Demo video (optional):** <!-- link -->

---

## Testing
### Automated
- [ ] Unit tests added/updated
- [ ] Integration tests added/updated
- [ ] All tests pass locally
- [ ] CI green

**Notes:**  
- <!-- ex: “Added unit tests for VisitService; integration test for /visits endpoint.” -->

### Manual Verification
**Steps I ran:**
1. <!-- ex: “Create a visit from UI” -->
2. <!-- ex: “Refresh student page” -->
3. <!-- ex: “Verify DB row created + totals updated” -->

**Expected result:**  
- <!-- what should happen -->

**Actual result:**  
- <!-- what happened -->

---

## Risk / Impact
**Risk level:**
- [ ] Low
- [ ] Medium
- [ ] High

**What could break?**
- <!-- ex: “Visit totals might be wrong if timezone conversion fails.” -->

**Mitigations:**
- <!-- ex: “Feature flag, DB constraint, input validation, fallback behavior.” -->

---

## Rollback Plan
- <!-- ex: “Revert PR + rollback migration with 2026_02_16_down.sql” -->
- <!-- ex: “Disable feature flag VISITS_ENABLED.” -->

---

## Reviewer Notes
**Areas to focus on:**
- <!-- ex: “Migration correctness + index choice; UI empty state.” -->

**Related issues / tickets:**
- Closes: <!-- #123 -->
- Related: <!-- #456 -->
