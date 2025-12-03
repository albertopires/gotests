## Example use

```
// Code on another project using this module

package main

import (
	"fmt"

	"github.com/albertopires/gotests/greetings"
)

func main() {
	// Get a greeting message and print it.
	message := greetings.Hello("Gladys")
	fmt.Println(message)
}
```

```
go get -v github.com/albertopires/gotests/greetings@v1.0.0
```

It's important to set GOPRIVATE to avoid proxy problems:
```
export `GOPRIVATE=github.com/albertopires`
```

It's also possible to have more than one source separated by a comma:
```
export GOPRIVATE=github.com/albertopires,github.com/otherrepo
```
