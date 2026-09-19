# Architecture

Provider adapters → ingestion → normalization → event store → ordering/reconstruction → validation/exception engine → investigation UI → evidence report/API.

The V1 keeps this architecture visible while using synthetic browser data. The next engineering step is a small backend with persistent storage and authenticated provider integrations.
