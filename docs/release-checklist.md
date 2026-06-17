# Release Checklist (Template)

Use this checklist before each deployment. Customize as needed for patch/minor/major releases.

- [ ] All related PRs merged and linked to release
- [ ] CI: All tests passing (unit, integration)
- [ ] Security scans: No critical vulnerabilities
- [ ] Migration steps documented (if applicable)
- [ ] Rollback plan documented and tested
- [ ] Release notes drafted and reviewed
- [ ] Monitoring dashboards and alerts in place
- [ ] Observability owner has validated metrics
- [ ] QA smoke tests prepared and owner assigned
- [ ] Communication plan: stakeholders & support notified
- [ ] Release Lead and Delivery Lead signed off

Post-release

- [ ] Run smoke tests in production
- [ ] Validate key metrics (errors, latency, usage)
- [ ] Document any incidents and next steps
- [ ] Update release notes with post-release findings
