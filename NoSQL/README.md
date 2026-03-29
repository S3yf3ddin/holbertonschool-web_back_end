# NoSQL

This project introduces NoSQL databases with a focus on MongoDB. It covers basic MongoDB shell commands as well as Python functions using PyMongo for interacting with MongoDB collections.

## Learning Objectives

- Understand what NoSQL means and how it differs from SQL
- Use MongoDB shell to perform CRUD operations
- Use PyMongo to interact with MongoDB from Python

## Requirements

- MongoDB 4.2
- Python 3.7+
- PyMongo 3.10+

## Files

### MongoDB Shell Scripts

| File | Description |
|------|-------------|
| `0-list_databases` | Lists all databases |
| `1-use_or_create_database` | Creates or switches to `my_db` database |
| `2-insert` | Inserts a document into the `school` collection |
| `3-all` | Lists all documents in the `school` collection |
| `4-match` | Lists all documents matching `name: "Holberton school"` |
| `5-count` | Counts all documents in the `school` collection |
| `6-update` | Updates documents with `name: "Holberton school"` to add an address field |
| `7-delete` | Deletes all documents with `name: "Holberton school"` |

### Python Scripts

| File | Description |
|------|-------------|
| `8-all.py` | `list_all(mongo_collection)` — returns a list of all documents in a collection |
| `9-insert_school.py` | `insert_school(mongo_collection, **kwargs)` — inserts a new document and returns its `_id` |
| `10-update_topics.py` | `update_topics(mongo_collection, name, topics)` — updates the `topics` field of all documents matching the given name |
| `11-schools_by_topic.py` | `schools_by_topic(mongo_collection, topic)` — returns all schools that have the given topic |
| `12-log_stats.py` | Prints statistics about Nginx logs stored in MongoDB (total logs, method counts, status checks) |
