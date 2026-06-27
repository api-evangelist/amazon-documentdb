---
title: "PostgreSQL 18 on Amazon Aurora and Amazon RDS: Performance enhancements"
url: "https://aws.amazon.com/blogs/database/postgresql-18-on-amazon-aurora-and-amazon-rds-performance-enhancements/"
date: "2026-06-17"
author: "Nazneen Jafri"
feed_url: "https://aws.amazon.com/blogs/database/feed/"
---
This post covers performance improvements in PostgreSQL 18 on Amazon Aurora and Amazon RDS, focusing on skip scan optimization that lets the query planner use multicolumn B-tree indexes more efficiently when leading columns are not specified in the WHERE clause. Enhanced EXPLAIN now includes buffer statistics by default and reports memory and disk usage for materialized CTEs, while self-join elimination automatically removes redundant inner joins on primary keys. Autovacuum gains finer control through new parameters like autovacuum_vacuum_max_threshold, vacuum_truncate as a server-wide setting, and autovacuum_worker_slots.
