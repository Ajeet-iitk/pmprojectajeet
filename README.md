# pmprojectajeet

A single saved query from a project-management database exercise: it reads the `key stats` view out of the `pmprojectajeet` schema.

## Contents

| File | What it is |
| --- | --- |
| `PMproject.sql` | `SELECT * FROM pmprojectajeet.\`key stats\`;` |

## Using it

The file is a query, not a schema - it expects a database that already has the `pmprojectajeet` schema and its `key stats` view. Run it with the MySQL client:

```bash
mysql -u <user> -p <database> < PMproject.sql
```

Or paste the statement into a workbench query tab.