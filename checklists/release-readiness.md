# Release Readiness Checklist

## Architecture

- [ ] Critical user and business flows are documented
- [ ] Service ownership is clear
- [ ] External dependencies are known
- [ ] Failure modes are listed

## CI/CD

- [ ] Pipeline is deterministic
- [ ] Rollback path is tested
- [ ] Required checks block release
- [ ] Secrets and environment variables are controlled

## QA strategy

- [ ] Critical flows have automated coverage
- [ ] API and integration risks are covered
- [ ] Regression scope is clear
- [ ] Edge cases are documented

## Observability

- [ ] Metrics exist for critical flows
- [ ] Logs are searchable and structured
- [ ] Alerts map to user/business impact
- [ ] Dashboards exist for release validation

## Incident readiness

- [ ] On-call ownership is clear
- [ ] Runbooks exist
- [ ] Escalation path is known
- [ ] Postmortem process exists
