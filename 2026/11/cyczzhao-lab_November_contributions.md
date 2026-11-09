# cyczzhao-lab's November Contributions

A summary of contributions by @cyczzhao-lab in November 2026:

- [tari-project/tari-ootle#3487](https://github.com/tari-project/tari-ootle/pull/3487): `fix(ootle_wasm): validate canonical public keys in parse_ootle_address and revealed_receiver` (tracked in `tari-project/special_contributions#509`).
- Security report: `GHSA-5hh3-fvmf-xxhq` (`tari-ootle` `tari_walletd` allows minting API keys with `SigningRequests(Approve)` and omits account-scope authorization in `handle_list` (`nfts.list`), fixed in [tari-project/tari-ootle#3545](https://github.com/tari-project/tari-ootle/pull/3545), tracked in `tari-project/special_contributions#514`). Testing was performed locally only; no shared network was touched.
- [tari-project/tari-ootle#3478](https://github.com/tari-project/tari-ootle/pull/3478): `fix(state_store_rocksdb): fix exclusive upper bounds in range queries and rewinds` (tracked in `tari-project/special_contributions#518`).
- [tari-project/tari-ootle#3486](https://github.com/tari-project/tari-ootle/pull/3486): `fix(transaction): charge invocation floor on stealth template functions and merge workspace keys` (tracked in `tari-project/special_contributions#519`).
