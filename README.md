## Hi there 👋

## Open Source Contributions

### Ceph - RADOS Gateway

- **[Ceph #69748](https://github.com/ceph/ceph/pull/69748)** - Prevent stale object versions from overwriting newer ObjectCache entries.
  - Concurrency and cache-consistency fix
  - Added regression coverage
  - **Merged into Ceph**
  - **Backport PRs:**
    - [Squid - #71059](https://github.com/ceph/ceph/pull/71059) 
    - [Tentacle - #71060](https://github.com/ceph/ceph/pull/71060)
    - [Umbrella - #71061](https://github.com/ceph/ceph/pull/71061)

- **[Ceph #71058](https://github.com/ceph/ceph/pull/71058)** - Version checks for RGW multisite metadata synchronization.
  - Addresses stale metadata updates and version ordering
  - Adds regression testing for concurrent synchronization
  - **Under review**
    
- **[Ceph #71143](https://github.com/ceph/ceph/pull/71143)** - Validate the cached version on metadata sync reads.
  - Fixes durable stale metadata on secondary zones (e.g. `403 AccessDenied` from an obsolete owner) caused by a lost cache-invalidation notification
  - Adds expected-version parameters to sync GET requests, and fixes `link_bucket()` writing entrypoints with an empty version tag
  - **Under review**
  - 
- **[Ceph #71349](https://github.com/ceph/ceph/pull/71349)** - Fix manifest end iterators before tail rule start.
  - Fixes an integer underflow in `RGWObjManifest::obj_iterator` for small objects fully contained in the head chunk
  - Added unit test coverage
  - **Under review**

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
