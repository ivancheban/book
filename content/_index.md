---
title: Hugo Book Theme
type: docs
---

# Ivan built this Hugo Book theme as an example.

This is a test page.

```go
package main

import (
    "fmt"
    "net/http"
)

func handler(w http.ResponseWriter, r *http.Request) {
    fmt.Fprintf(w, "Hi there, I love %s!", r.URL.Path[1:])
}

func main() {
    http.HandleFunc("/", handler)
    http.ListenAndServe(":8080", nil)
}
```

{{< tabs "uniqueid" >}}
{{< tab "Android" >}}
# Android

This is a tab for **Android** content.

{{< /tab >}}

{{< tab "iOS" >}}

# iOS

This is a tab for **iOS** content.

{{< /tab >}}

{{< tab "Windows" >}}

# Windows

This is a tab for **Windows** content.

{{< /tab >}}
{{< /tabs >}}