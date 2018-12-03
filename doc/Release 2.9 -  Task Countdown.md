# Task Countdown

Count of tasks, known to be required to progress towards a final release 2.9.0 of Riak.  The release phase is split into four parts:

- Private Release Candidate - preparing a branch which can be subject to non-production testing by the primary Riak customers involved in the development cycle.  This will allow for further testing under different constraints, and work to commence on exploiting the required features.

- Public Release Candidate - provide a release candidate that has passed sufficient testing to allow for proving in non-production environments by a broader customer base.

- Release 2.9.0 - a quality-assured first release of the series.

- Subsequent Releases - any features deferred from 2.9.0, or fixes discovered post the Release of 2.9.0 may lead to subsequent releases.


## Private Release Candidate


Task | Status
:-------------------------|:-------------------------:
Complete first round of riak functional test | ongoing - mas
Risk assessment following riak functional test | ongoing - mas
Merge in hot_backup work and test | pending - mas
Configuration guidance for exposed Leveled and Tictac AAE features | pending - mas
Tagged release of `leveled` and `kv_index_tictactree` repos | pending - mas
Provide preview of overview notes for release | ongoing - mas


## Public Release Candidate

Task | Status
:-------------------------|:-------------------------:
Access to A-D replication fixes | ongoing - bet365
Add enterprise leveldb into the build for Riak (with hot backup feature) | unassigned
Creation of actual develop 2.9 branch | unassigned
Tag release candidate | unassigned
Code and test review of get_fsm changes | unassigned
Volume test showing bitcask comparison (not just leveled vs leveldb) | pending - mas
Testing in more live-like Spine environment (with larger disks) | ongoing - nhs
Testing in more live-like SuS environment | pending - nhs
Completion of HTTP API for Cluster-wide AAE | ongoing - rdb
Verify previous volume test results on actual release candidate | unassigned
Two rounds of riak functional test on actual release candidate | unassigned
Compatibility testing with Riak CS | unassigned
Publish preview of release notes | unassigned
Writing of migration guidance, wih publication of volume test results for migration | pending - mas
Leveled configuration when in multi-backend mode | unassigned


## Release 2.9.0


Task | Status
:-------------------------|:-------------------------:|
Additional independent property-based testing of leveled (focused on file-management actors) | pending - quviq
Publication of release notes and documentation updates |  unassigned
Acceptance of PRs into basho repo | unassigned

## Subsequent Releases

To be determined.
