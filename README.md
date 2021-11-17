# reborn-contracts

# Reborn

A simple ‘zap’ in/out router for token staking, swap and migration.

Example calls, which can also be combined using `batch()`:

**Stake Soul to:**

* **Geist** **(Enchant)**: `stakeSoulToGeist()`
* **Corpus** **(Enchant or crXsushi)**: `stakeSoulToCorpus()`, `stakeSoulToGeistToCorpus()`
* **Scream** **(Soul or Enchant)**: `soulToGeist()`, `stakeSoulToGeist()`

**Turn tokens or ETH into SLP:**

* `zapIn()`, `zapOut()` 
* **Corpus (SLP)**: `zapToCorpus()`
