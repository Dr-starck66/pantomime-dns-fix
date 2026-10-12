# ASTRA MASTER GATE Ω — isolated proof run

This harmless pull request tests the actual GitHub Actions pipeline without merging to production. The workflow executes the gate's regression tests, then audits all applicable site bricks in fail-closed mode. A missing proof must produce UNVERIFIED and a non-zero strict exit code; never greenwash such a result.

Expected initial site result: PARTIAL or FAIL until every required site-specific proof has been configured.
