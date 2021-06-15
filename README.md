# cron

Added goroutine pool on the basis of github.com/robfig/cron to prevent unlimited growth of the number of goroutines.

Import it in your program as:
```go
import "github.com/haiheipijuan/cron/v3"
```
It requires Go 1.11 or later due to usage of Go Modules.

Refer to the documentation here:
http://godoc.org/github.com/robfig/cron

The rest of this document describes the the advances in v3 and a list of
breaking changes for users that wish to upgrade from an earlier version.
