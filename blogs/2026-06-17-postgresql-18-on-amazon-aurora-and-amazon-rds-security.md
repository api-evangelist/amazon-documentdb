---
title: "PostgreSQL 18 on Amazon Aurora and Amazon RDS: Security, monitoring, and developer enhancements"
url: "https://aws.amazon.com/blogs/database/postgresql-18-on-amazon-aurora-and-amazon-rds-security-monitoring-and-developer-enhancements/"
date: "2026-06-17"
author: "Nazneen Jafri"
feed_url: "https://aws.amazon.com/blogs/database/feed/"
---
Part 2 explores security, monitoring, developer, and replication features in PostgreSQL 18, where MD5 password authentication is deprecated in favor of SCRAM-SHA-256 with a new md5_password_warnings parameter, and pg_upgrade now automatically transfers optimizer statistics from the old cluster to the new one. UUIDv7 provides timestamp-ordered unique identifiers suitable for primary keys, the default logical replication streaming mode shifts to parallel, and idle_replication_slot_timeout prevents disk exhaustion from abandoned slots. COPY adds REJECT_LIMIT and LOG_VERBOSITY silent mode, while RETURNING clauses now support OLD and NEW aliases for capturing before-and-after values.
