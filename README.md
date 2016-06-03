# binlogEventStats

A fake slave that generates stats over the binary log streaming.

## Requirements

All you need is:

```
pip install mysql-replication
```

## Want to help?

Read the [docs](https://python-mysql-replication.readthedocs.org/en/latest/).


## Limitations

Use `binlog_format = row`, otherwise it will explode in your face.
