# kotoba-actor-sdk

Shared SDK boundary for actors deployed through app-aozora.  This is not a
domain actor and has no DID or deployment entry of its own.

- `sdk/` — substrate SDK
- `auth/` — PDS session adapter for the SDK
- `mock/` — in-memory test double

Domain actors depend on these packages from their own `etzhayyim` repositories.
`app-aozora` must not retain source mirrors of them.
