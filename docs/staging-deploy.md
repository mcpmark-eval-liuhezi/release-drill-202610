# Staging Deployment Procedure

This runbook covers a routine staging deployment for the release drill.

## Steps

1. Confirm the release candidate is built and smoke tests pass on the artifact.
2. Verify the staging URL in this runbook matches the environment being deployed to.
3. Announce the deployment window in the release channel.
4. Deploy the release candidate to staging.
5. Run the staging smoke suite against the deployed build.
6. Record the deployment result in the release log and tag the release owner for sign-off.
