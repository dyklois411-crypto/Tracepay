# API Contract

Future ingestion endpoint: `POST /v1/events`.

Expected fields: `transaction_id`, `timestamp`, `provider`, `amount`, `currency`, `event_type`, `event_status`, `reference`, `source`.

Before real payment data is accepted, add authentication, authorization, schema validation, idempotency, signature verification, rate limits, audit logging and monitoring.
