# GORM Sqlite Driver

![CI](https://github.com/go-gorm/sqlite/workflows/CI/badge.svg)

## USAGE

It's a pure golang implement for gorm.io/driver/sqlite. This implement don't need cgo.

```go
import (
  "github.com/zhfreal/sqlite"
  "gorm.io/gorm"
)

// github.com/mattn/go-sqlite3
db, err := gorm.Open(sqlite.Open("gorm.db"), &gorm.Config{})
```

Checkout [https://gorm.io](https://gorm.io) for details.
