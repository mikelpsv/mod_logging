# mod_logging
## Overview

mod_logging is a small module for logging the operation of the application

## Use

```
import (
  l "github.com/mikelpsv/mod_logging"
)


func main() {
  l.Init("log/info.log", "log/error.log")
}

func somefunc(){
  l.Trace.Println(...)
  l.Info.Println(...)
  l.Warning.Println(...)
  l.Error.Println(...)
  
}
```
