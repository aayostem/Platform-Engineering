# Platform

The Internal Developer Platform built across Phases 07–10. This is where
Phases 02–06's savings become permanent instead of reverting six months
after the engagement ends.

- `backstage/` — the IDP itself: catalog entries for both stacks
  (`catalog/`), the golden-path scaffolder template (`templates/`), and the
  FinOps cost-card plugin (`plugins/finops/`) built in Phase 10.
- `karpenter/nodepools/` — the NodePool and EC2NodeClass manifests from
  Phase 04, general-purpose and GPU, referenced by both stacks.
- `kubecost/` — Helm values and alert configuration for the Kubecost
  deployment from Phase 03.

Populated incrementally as each phase is recorded — see that phase's
`iac/` folder for the diff that lands here.
# Platform-Engineering
