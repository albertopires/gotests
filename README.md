## Example use

```
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

it's important to set export `GOPRIVATE=github.com/albertopires` to avoid proxy problems.