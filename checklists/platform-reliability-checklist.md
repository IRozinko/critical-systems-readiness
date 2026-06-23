# Platform Reliability Checklist

## Ownership

- [ ] Every critical service has an owner
- [ ] Runtime dependencies are documented
- [ ] Escalation path is known
- [ ] On-call expectations are clear

## Infrastructure

- [ ] Infrastructure changes are reviewed
- [ ] Terraform/IaC state is controlled
- [ ] Environments are reproducible
- [ ] Secrets are rotated and scoped

## Observability

- [ ] Golden signals exist for critical services
- [ ] Logs are structured and searchable
- [ ] Dashboards show business-critical flow health
- [ ] Alerts are actionable and owned

## Reliability controls

- [ ] SLOs/SLIs exist for critical flows
- [ ] Rollback strategy is tested
- [ ] Failure modes are documented
- [ ] Capacity and scaling assumptions are known

## Delivery

- [ ] CI/CD gates reflect production risk
- [ ] Deployment strategy is explicit
- [ ] Release notes include operational impact
- [ ] Post-release validation exists
