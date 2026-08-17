# AIPM GitHub Forward TEST_ONLY Task

This is a transport/authorization-boundary test artifact for the approved GitHub Forward feasibility lane. It is intentionally expired and MUST NOT be executed.

```json
{"schema_version":"0.1","packet_type":"TASK","packet_id":"f3ecfca0-c104-40c6-beee-2c4b6eed91b3","work_item_id":"github-forward-l6-slice3-test-only","attempt_id":"b7f25ce6-f64a-4d17-9e9b-a0ae539199f3","worker":"windows_claude_code_oneshot_worker","goal":"TEST_ONLY transport verification. Do not execute; this Task is intentionally expired.","success_criteria":["GitHub file creation and exact readback only"],"failure_criteria":["Any Worker or Claude execution","Any mutation outside this TEST_ONLY GitHub artifact"],"scope":["hirocando/intro public test repository","GitHub Forward feasibility lane only"],"constraints":["TEST_ONLY","INTENTIONALLY_EXPIRED","NO_WORKER_EXECUTION","NO_CLAUDE_EXECUTION"],"inputs":[],"evidence_refs":[],"allowed_actions":[],"prohibited_actions":["Bash","Write","Edit","Agent"],"human_gate_conditions":["Any attempt to execute this Task must STOP"],"expected_output":"No execution output. This artifact exists only for transport/authorization-boundary verification.","ack_deadline_utc":"2026-08-17T02:30:00Z","result_deadline_utc":"2026-08-17T02:30:00Z"}
```
