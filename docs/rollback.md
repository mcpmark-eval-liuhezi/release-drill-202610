# Rollback Procedure

This runbook covers rolling back a bad deployment during the release drill.

## Steps

1. Confirm the failure with smoke test results or the on-call alert.
2. Notify the release channel that a rollback is starting.
3. Re-deploy the last known good release candidate.
4. Verify the staging environment is healthy again with the smoke suite.
5. Record the rollback in the release log and note the root cause for follow-up.
