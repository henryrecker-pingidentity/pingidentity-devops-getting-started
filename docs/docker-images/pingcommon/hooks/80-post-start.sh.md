
# Ping Identity DevOps `pingcommon` Hook - `80-post-start.sh`
 This script is started in the background immediately before 
 the server within the container is started
 This is useful to implement any logic that needs to occur after the
 server is up and running
 For example, enabling replication in PingDirectory, initializing Sync 
 Pipes in PingDataSync or issuing admin API calls to PingFederate or PingAccess

---
This document is auto-generated from _[pingcommon/opt/staging/hooks/80-post-start.sh](https://github.com/pingidentity/pingidentity-docker-builds/blob/master/pingcommon/opt/staging/hooks/80-post-start.sh)_

Copyright © 2021 Ping Identity Corporation. All rights reserved.
