# Redis (15 h 34)

**course:** [click here to see the course](https://www.udemy.com/course/redis-the-complete-developers-guide-p)

## 17-03-2025

### Get Started Here! (7 classes / 14 min)

* Hello and Welcome!
* Join Our Community!
* Course Resources
* Why Use Redis?
* Initial Setup
* A Touch More Setup
* Running RBook Locally

### Commands for Adding and Querying Data (15 classes / 1 h 2 min)

* Basic Commands
* Documentation on Commands
* Essentials of Commands3 preguntas
* Variations of SET
* Use Case of Expiration Options
* Setting Multiple Keys
* GET and MGET
* String Ranges
* Are These Commands Even Useful?
* Dealing with Numbers
* Again... Why do These Commands Exist?
* Completed Notes
* Using a Completed Notebook
* Exercises
* A Few Exercises
* Exercise Solutions

### E-Commerce App Setup (8 classes / 48 min)

* E-Commerce App Source Code Download
* Don't Skip This Video
* Redis Client Libraries
* First Implementation Task
* Redis Design Methodology
* Key Naming Methodology
* Adding Page Caching
* Better Key Generation


## 18-03-2025

### Local Redis Setup (2 classes / 2 min)

* Installing on MacOS
* Installing on Windows

### Hash Data Structures (5 classes / 14 min)

* Hashes in Redis
* Storing and Retrieving Hashes
* Deleting Hash Data
* Numbers in Hashes
* Completed Notes

### Redis Has Gotcha's! (3 classes / 17 min)

* Slightly Unpredictable HSET and HGETALL
* Issues with HSET
* Issues with HGETALL

### Powerful Design Patterns (13 classes / 1 h 26 min)

* App Overview
* Reducing the Design to Queries
* What Data Type for Each Resource
* When to use Hashes2 preguntas
* Create User Implementation
* Serialization and Deserialization
* Adding Serialize
* Fetching a User
* Implementing Sessions
* Fetching a Saved Session
* Creating Sessions
* Serializing Date Times
* Storing Items
* Fetching a Single Item

### Pipelining Commands (3 classes / 14 min)

* Batching Commands with Pipelines
* Running Multiple Commands at the Same Time
* Executing a Pipeline

### Enforcing Uniqueness with Sets (9 classes / 27 min)

* Basics of Sets
* Union of Sets
* Intersection of Sets
* Difference of Sets
* Store Variations
* Checking for an Element in a Set
* Scanning a Set
* Completed Notes
* Most Common Use Cases of Sets

## 18-03-2025

### A Little Set Implementation (6 classes / 28 min)

* Requiring Unique User Names
* Adding a Like System
* How to Count the Number of Likes?
* Updating Like Quantities
* Showing Liked Items
* Showing Common Liked Items

### Organizing Data with Sorted Sets (7 classes / 25 min)

* Sorted Sets
* Adding and Removing Members
* Finding a Range of Scores
* Removing the Highest and Lowest Members
* Updating Scores
* Querying a Sorted Set
* Completed Notes

### Practice Time with Sorted Sets! (10 classes / 1 h)

* Sorted Set Use Cases
* Reminder on the Auth Flow
* Storing Usernames
* Kind of Storing Strings in Sorted Sets
* Converting User IDs
* Plan for Showing Most Viewed Items
* Initializing Views on Item Creation
* Incrementing View Counters
* Items by Ending Soonest
* Querying for Ending Soonest

## 19-03-2025

### From Relational Data to Redis (9 classes / 58 min)

* Loading Relational Data
* Relational Data with SORT
* The Sort Command
* Terminology Around Sort
* Specifying the BY Argument
* Joining Data with Sort
* A Few More Arguments
* Parsing SORT Output
* Completed Notes

### HyperLogLog Structures (3 classes / 16 min)

* HyperLogsLogs
* When to use HyperLogsLogs
* HyperLogsLogs in Action

### Storing Collections with Lists (9 classes / 56 min)

* Lists
* Reading and Writing Data to a List
* Ranges and Searches
* Trimming Lists
* Removing Elements
* List Use Cases
* Using Lists in Our App
* Serializing and Deserializing Bids
* Retrieving Bid Histories

## 20-03-2025

### More Practice with the E-Commerce App (12 classes / 1 h)

* More on Bids
* Validating Bids
* Updating Items with Bids
* Issues with Bids
* Understanding Concurrency Issues
* Applying Atomic Updates
* Transactions
* Watching a Key with Transactions
* Isolated Connections for Transactions
* Solving Multiple Bids with a Transaction
* Items by Price
* More on Items by Price

### Extending Redis with Scripting (12 classes / 1 h 15 min)

* Lua Scripting
* Basics of Lua
* Handling Arrays
* Handling Tables
* Loading and Executing Scripts
* Providing Arguments
* Providing Key lists
* When to Use Scripts
* Custom Scripts with Node-Redis
* Lua Script Integration
* Creating a View-Incrementing Script
* Code Cleanup

## 21-03-2025

### Understanding and Solving Concurrency Issues (14 classes / 1 h 20 min)

* Concurrency Revisited
* Issues with WATCH
* Overview of a Lock
* Understanding the Goal
* Implementing WithLock
* Using WithLock
* It Works!
* Automatically Expiring Locks
* Another Lock Issue
* Solving Accidental Unlocks
* Adding an Unlock Script
* One Last Issue
* Providing Expiration Signals
* Alternate Expiration Solution

## 24-03-2025

### Querying Data with RediSearch (13 classes / 59 min)

* Redis Modules
* Redis Core vs Redis Stack
* Using Modules in Production
* Overview on Search
* Creating and Using an Index
* Details on Indexes
* Index Field Types
* Numeric Queries
* Tag Queries
* Text Queries
* Fuzzy Search
* Prefix Search
* Pre-Processing Search Criteria

### Search in Action (14 classes / 1 h 12 min)

* Search Implementation
* The Create Index Function
* When to Create the Index?
* Parsing the Search Term
* Executing the Search
* Seeding Some Fake Data
* RediSearch and TF-IDF
* Applying Weights to Fields
* Understanding Queries with EXPLAIN
* Query Performance with PROFILE
* Sorting and Searching
* Updating an Existing Index
* Executing the Search
* Deserializing Search Results

## 25-03-2025

### Service Communication with Streams (13 classes / 1 h)

* Streams
* Use Case of Streams
* Adding Messages to a Stream
* Consuming Streams with XREAD
* Blocking Reads
* An XREAD Shortcut
* A Little Gotcha Around Streams
* Reading Streams with XRANGE
* Issues with Standard Streams
* Consumer Groups
* Creating and Inspecting Consumer Groups
* Consumer Groups in Action
* Claiming Expired Messages

### Bonus! (1 classes / 1 min)

* Bonus!