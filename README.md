## Hi there 👋

## Open Source Contributions

### Ceph - RADOS Gateway

| PR | Description | Highlights | Status | Backports |
|---|---|---|---|---|
| [#69748](https://github.com/ceph/ceph/pull/69748) | Prevent stale object versions from overwriting newer ObjectCache entries | Fixes a concurrency/cache-consistency race; adds regression test coverage | **Merged into main** | Pending: [Squid #71059](https://github.com/ceph/ceph/pull/71059), [Tentacle #71060](https://github.com/ceph/ceph/pull/71060), [Umbrella #71061](https://github.com/ceph/ceph/pull/71061) |
| [#71058](https://github.com/ceph/ceph/pull/71058) | Add version checks for RGW multisite metadata synchronization | Addresses stale metadata updates and version ordering; adds regression testing for concurrent sync | Under review | — |
| [#71143](https://github.com/ceph/ceph/pull/71143) | Validate the cached version on metadata sync reads | Fixes durable stale metadata on secondary zones (e.g. `403 AccessDenied` from an obsolete owner); adds expected-version params to sync GET requests; fixes `link_bucket()` writing entrypoints with an empty version tag | Under review | — |
| [#71349](https://github.com/ceph/ceph/pull/71349) | Fix manifest end iterators before tail rule start | Fixes an integer underflow in `RGWObjManifest::obj_iterator` for small objects fully in the head chunk; adds unit test coverage | Under review | — |

<!--
**SaravananPalanisamyRWTH/SaravananPalanisamyRWTH** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
