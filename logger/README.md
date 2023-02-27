```
package main

import (
	"log"
	"github.com/kzeromiddle/logger"
)

func main() {
	log.SetFlags(log.LstdFlags | log.Lshortfile)
	l := logger.Logger{
		// Directory: "logs",
		Prefix:    defineProgramName,
	}
	l.InitStandardLogger(logger.FILE)
	// log.Println("log test")
}
```
