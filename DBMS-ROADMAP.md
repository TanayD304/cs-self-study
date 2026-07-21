# Database Management Systems (DBMS) Roadmap (Interview Focused)

> Primary Resource: TakeUForward (TUF+) DBMS
> Goal: SDE Interviews (Google, Amazon, Microsoft, Meta, Uber, Atlassian, etc.)

---

# Legend

✅ Covered in TUF+

➕ Additional (Important)

⭐ Must Know

💡 Good to Know

🔹 Optional / Advanced

---

# Phase 1 — DBMS Foundations ⭐

## Database Basics

- [ ] ✅⭐ Data vs Information vs Database
- [ ] ✅⭐ Types of Databases
- [ ] ✅⭐ What is DBMS?
- [ ] ✅⭐ Advantages & Disadvantages of DBMS
- [ ] ✅⭐ Data Abstraction
- [ ] ✅⭐ Three Schema Architecture
- [ ] ✅⭐ DBMS Architecture
- [ ] ✅⭐ Database Users

---

## ➕ Additional

- [ ] ➕⭐ OLTP vs File System
- [ ] ➕💡 Database Engine Overview
- [ ] ➕💡 RDBMS vs NoSQL Comparison

---

# Phase 2 — Data Modeling ⭐⭐

## ER Modeling

- [ ] ✅⭐⭐ DBMS Interfaces
- [ ] ✅⭐⭐ Data Models
- [ ] ✅⭐⭐ ER Model
- [ ] ✅⭐⭐ Entities
- [ ] ✅⭐⭐ Attributes
- [ ] ✅⭐⭐ Relationships
- [ ] ✅⭐⭐ Cardinality
- [ ] ✅⭐⭐ Participation Constraints
- [ ] ✅⭐⭐ EER Model
- [ ] ✅⭐⭐ Inheritance
- [ ] ✅⭐⭐ Relational Model
- [ ] ✅⭐⭐ ER Diagram Design

---

## ➕ Additional

- [ ] ➕⭐ Weak Entity
- [ ] ➕⭐ Composite Attribute
- [ ] ➕💡 Derived Attribute

---

# Phase 3 — Relational Model ⭐⭐⭐

## Keys

- [ ] ✅⭐⭐ Super Key
- [ ] ✅⭐⭐ Candidate Key
- [ ] ✅⭐⭐ Primary Key
- [ ] ✅⭐⭐ Alternate Key
- [ ] ✅⭐⭐ Foreign Key

## Functional Dependency

- [ ] ✅⭐⭐ Functional Dependency
- [ ] ✅⭐⭐ Armstrong's Axioms
- [ ] ✅⭐⭐ Inference Rules
- [ ] ✅⭐⭐ Attribute Closure

## Normalization

- [ ] ✅⭐⭐ 1NF
- [ ] ✅⭐⭐ 2NF
- [ ] ✅⭐⭐ 3NF
- [ ] ✅⭐⭐ BCNF
- [ ] ✅⭐⭐ Denormalization

---

## ➕ Additional

- [ ] ➕⭐ Composite Keys
- [ ] ➕⭐ Surrogate Keys
- [ ] ➕⭐ Natural Keys
- [ ] ➕⭐ Foreign Key Actions (CASCADE, RESTRICT, SET NULL)

---

# Phase 4 — SQL ⭐⭐⭐⭐⭐

## SQL Basics

- [ ] ✅⭐⭐ SELECT
- [ ] ✅⭐⭐ WHERE
- [ ] ✅⭐⭐ ORDER BY
- [ ] ✅⭐⭐ GROUP BY
- [ ] ✅⭐⭐ HAVING
- [ ] ✅⭐⭐ DISTINCT

## Operators

- [ ] ✅⭐⭐ Comparison Operators
- [ ] ✅⭐⭐ Logical Operators
- [ ] ✅⭐⭐ Aggregate Functions

## Joins

- [ ] ✅⭐⭐ Inner Join
- [ ] ✅⭐⭐ Left Join
- [ ] ✅⭐⭐ Right Join
- [ ] ✅⭐⭐ Full Join
- [ ] ✅⭐⭐ Self Join
- [ ] ✅⭐⭐ Cross Join

## Advanced SQL

- [ ] ✅⭐⭐ UNION
- [ ] ✅⭐⭐ UNION ALL
- [ ] ✅⭐⭐ Views
- [ ] ✅⭐⭐ Materialized Views
- [ ] ✅⭐⭐ Subqueries
- [ ] ✅⭐⭐ Correlated Subqueries

---

## ➕ Important SQL Additions

- [ ] ➕⭐⭐ CTE (WITH)
- [ ] ➕⭐⭐ Window Functions
- [ ] ➕⭐⭐ ROW_NUMBER()
- [ ] ➕⭐⭐ RANK()
- [ ] ➕⭐⭐ DENSE_RANK()
- [ ] ➕⭐ LEAD()
- [ ] ➕⭐ LAG()
- [ ] ➕⭐ CASE WHEN
- [ ] ➕⭐ COALESCE()
- [ ] ➕⭐ NULLIF()

---

## SQL Interview Questions

- [ ] ➕⭐⭐ EXISTS vs IN
- [ ] ➕⭐⭐ DELETE vs TRUNCATE vs DROP
- [ ] ➕⭐⭐ CHAR vs VARCHAR
- [ ] ➕⭐⭐ COUNT(*) vs COUNT(column)
- [ ] ➕⭐⭐ WHERE vs HAVING
- [ ] ➕⭐⭐ UNION vs UNION ALL
- [ ] ➕⭐⭐ Primary Key vs Unique Key
- [ ] ➕⭐ ANY vs ALL
- [ ] ➕⭐ LIMIT vs TOP

---

## SQL Execution

- [ ] ➕⭐⭐ SQL Execution Order
- [ ] ➕⭐⭐ EXPLAIN
- [ ] ➕⭐⭐ EXPLAIN ANALYZE

---

# Phase 5 — Query Processing ⭐⭐⭐

- [ ] ✅⭐⭐ Query Processing
- [ ] ✅⭐⭐ Query Optimization
- [ ] ✅⭐⭐ Advanced Query Optimization

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Table Scan
- [ ] ➕⭐⭐ Index Scan
- [ ] ➕⭐⭐ Nested Loop Join
- [ ] ➕⭐⭐ Hash Join
- [ ] ➕⭐ Merge Join
- [ ] ➕⭐ Cost Based Optimizer

---

# Phase 6 — Indexing ⭐⭐⭐⭐⭐

## Indexes

- [ ] ✅⭐⭐ Database Indexing
- [ ] ✅⭐⭐ Types of Indexing
- [ ] ✅⭐⭐ Indexing Techniques
- [ ] ✅⭐⭐ B Trees
- [ ] ✅⭐⭐ B+ Trees

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Clustered Index
- [ ] ➕⭐⭐ Non Clustered Index
- [ ] ➕⭐⭐ Composite Index
- [ ] ➕⭐⭐ Covering Index
- [ ] ➕⭐ Unique Index
- [ ] ➕⭐ Partial Index
- [ ] ➕⭐ Bitmap Index
- [ ] ➕⭐ Hash Index

---

# Phase 7 — Transactions ⭐⭐⭐⭐⭐

## ACID

- [ ] ✅⭐⭐ ACID Properties

## Transactions

- [ ] ✅⭐⭐ Transactions
- [ ] ✅⭐⭐ Concurrency Control
- [ ] ✅⭐⭐ Shared Locks
- [ ] ✅⭐⭐ Exclusive Locks
- [ ] ✅⭐⭐ Timestamp Ordering
- [ ] ✅⭐⭐ Deadlocks
- [ ] ✅⭐⭐ Starvation
- [ ] ✅⭐⭐ Serializability
- [ ] ✅⭐⭐ Scheduling
- [ ] ✅⭐⭐ Serialization Graph
- [ ] ✅⭐⭐ Isolation Levels

---

## ➕ Important Additions

- [ ] ➕⭐⭐ MVCC (Multi Version Concurrency Control)
- [ ] ➕⭐⭐ Optimistic Locking
- [ ] ➕⭐⭐ Pessimistic Locking
- [ ] ➕⭐ Phantom Reads
- [ ] ➕⭐ Dirty Reads
- [ ] ➕⭐ Non Repeatable Reads

---

# Phase 8 — Distributed Databases ⭐⭐⭐

- [ ] ✅⭐⭐ Distributed Databases
- [ ] ✅⭐⭐ Architecture
- [ ] ✅⭐⭐ Data Distribution
- [ ] ✅⭐⭐ Replication
- [ ] ✅⭐⭐ Fault Tolerance
- [ ] ✅⭐⭐ Load Balancing

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Leader-Follower Replication
- [ ] ➕⭐⭐ Read Replicas
- [ ] ➕⭐⭐ Consistency Models
- [ ] ➕⭐ Multi Master Replication
- [ ] ➕⭐ Eventual Consistency

---

# Phase 9 — NoSQL ⭐⭐⭐

- [ ] ✅⭐⭐ NoSQL
- [ ] ✅⭐⭐ BASE
- [ ] ✅⭐⭐ Graph Databases
- [ ] ✅⭐⭐ In Memory Databases
- [ ] ✅⭐⭐ Partitioning
- [ ] ✅⭐⭐ Sharding

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Document Databases
- [ ] ➕⭐⭐ Key Value Stores
- [ ] ➕⭐⭐ Column Family Databases
- [ ] ➕⭐ Time Series Databases
- [ ] ➕⭐ Vector Databases

---

# Phase 10 — Recovery ⭐⭐

- [ ] ✅⭐⭐ Recovery
- [ ] ✅⭐⭐ Backup

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Write Ahead Logging (WAL)
- [ ] ➕⭐⭐ Checkpoints
- [ ] ➕⭐ Crash Recovery

---

# Phase 11 — Performance ⭐⭐⭐

- [ ] ✅⭐⭐ Performance Tuning
- [ ] ✅⭐⭐ Monitoring
- [ ] ✅⭐⭐ Database Caching
- [ ] ✅⭐⭐ Caching Strategies

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Connection Pooling
- [ ] ➕⭐⭐ Prepared Statements
- [ ] ➕⭐⭐ Batch Inserts
- [ ] ➕⭐⭐ Bulk Operations
- [ ] ➕⭐ Read Through Cache
- [ ] ➕⭐ Write Through Cache
- [ ] ➕⭐ Write Back Cache

---

# Phase 12 — Security ⭐⭐

- [ ] ✅⭐⭐ Database Security
- [ ] ✅⭐⭐ Encryption
- [ ] ✅⭐⭐ Data Masking
- [ ] ✅⭐⭐ RBAC

---

## ➕ Important Additions

- [ ] ➕⭐⭐ SQL Injection
- [ ] ➕⭐⭐ Parameterized Queries
- [ ] ➕⭐ Principle of Least Privilege

---

# Phase 13 — Scalability ⭐⭐⭐

- [ ] ✅⭐⭐ Scaling
- [ ] ✅⭐⭐ DBaaS
- [ ] ✅⭐⭐ Big Data

---

## ➕ Important Additions

- [ ] ➕⭐⭐ Horizontal Scaling
- [ ] ➕⭐⭐ Vertical Scaling
- [ ] ➕⭐⭐ Read Scaling
- [ ] ➕⭐⭐ Write Scaling
- [ ] ➕⭐ Consistent Hashing

---

# Phase 14 — Data Warehousing ⭐

- [ ] ✅ Data Warehousing
- [ ] ✅ Migration
- [ ] ✅ Event Driven Architecture

---

## ➕ Important Additions

- [ ] ➕⭐ OLTP vs OLAP
- [ ] ➕⭐ Star Schema
- [ ] ➕⭐ Snowflake Schema

---

# Phase 15 — Backend Database Concepts ⭐⭐⭐

## ORM

- [ ] ➕⭐⭐ ORM Basics
- [ ] ➕⭐⭐ Hibernate
- [ ] ➕⭐⭐ JPA Concepts
- [ ] ➕⭐ Lazy Loading
- [ ] ➕⭐ Eager Loading

---

## Backend Patterns

- [ ] ➕⭐⭐ N+1 Query Problem
- [ ] ➕⭐⭐ Pagination (OFFSET)
- [ ] ➕⭐⭐ Cursor Pagination
- [ ] ➕⭐⭐ Soft Delete
- [ ] ➕⭐⭐ Audit Tables
- [ ] ➕⭐⭐ UUID vs Auto Increment IDs

---

## Search

- [ ] ➕⭐ Elasticsearch vs SQL
- [ ] ➕⭐ Full Text Search

---

# Phase 16 — Database Internals 💡

- [ ] ➕💡 Database Pages
- [ ] ➕💡 Slotted Pages
- [ ] ➕💡 Heap Files
- [ ] ➕💡 Buffer Pool
- [ ] ➕💡 Buffer Manager
- [ ] ➕💡 Storage Engine Overview

---

# Optional (Advanced Database Engineering)

- [ ] 🔹 Bloom Filters
- [ ] 🔹 LSM Trees
- [ ] 🔹 SSTables
- [ ] 🔹 Columnar Storage
- [ ] 🔹 Query Planner Internals
- [ ] 🔹 Cost Based Optimizer Internals
- [ ] 🔹 Raft
- [ ] 🔹 Paxos
- [ ] 🔹 CQRS
- [ ] 🔹 Event Sourcing

---

# Final Interview Revision Checklist ⭐⭐⭐⭐⭐

## Absolute Must Know

- [ ] DBMS Architecture
- [ ] ER Diagram
- [ ] Keys
- [ ] Functional Dependency
- [ ] Normalization
- [ ] SQL
- [ ] Joins
- [ ] Aggregates
- [ ] Views
- [ ] Subqueries
- [ ] SQL Execution Order
- [ ] EXISTS vs IN
- [ ] DELETE vs TRUNCATE vs DROP
- [ ] CHAR vs VARCHAR
- [ ] COUNT(*) vs COUNT(column)
- [ ] Query Optimization
- [ ] EXPLAIN
- [ ] Clustered vs Non Clustered Index
- [ ] Composite Index
- [ ] Covering Index
- [ ] ACID
- [ ] Transactions
- [ ] Isolation Levels
- [ ] Deadlocks
- [ ] MVCC
- [ ] Locking
- [ ] CAP Theorem
- [ ] Sharding
- [ ] Partitioning
- [ ] Replication
- [ ] Read Replicas
- [ ] NoSQL Types
- [ ] Caching
- [ ] Connection Pooling
- [ ] SQL Injection Prevention
- [ ] ORM Basics
- [ ] Pagination
- [ ] N+1 Query Problem

---

# Completion Goal

- TUF+ Roadmap: **100%**
- Important Additions: **100%**
- Optional Topics: **As Needed (Backend/System Design Focus)**
