---
title: "Blog Features Showcase"
date: 2026-03-11
description: "A quick tour of the shortcodes and features available on this blog."
tags:
  - introduction
  - tutorial
categories:
  - General
draft: false
---

## Callouts

Use callouts to highlight important information.

{{< callout type="info" >}}
This is an **info** callout. Great for tips and notes.
{{< /callout >}}

{{< callout type="warning" >}}
This is a **warning** callout. Use it to flag things to watch out for.
{{< /callout >}}

{{< callout type="error" >}}
This is an **error** callout. Use it for critical issues.
{{< /callout >}}

## Keyboard Shortcuts

You can render inline keyboard keys like {{< kbd "Ctrl+C" >}}, {{< kbd "Cmd+Space" >}}, or {{< kbd "Enter" >}}.

Useful for documenting CLI workflows or writing tutorials.

## Images with Captions

Use the `figure` shortcode for images with optional captions and width control:

{{< figure src="https://picsum.photos/800/400" alt="A sample image" caption="**Figure 1**: A placeholder image from Lorem Picsum." width="100%" >}}

## Code Blocks

Syntax highlighting works out of the box:

```go {filename="main.go"}
package main

import "fmt"

func main() {
    fmt.Println("Hello, 150ml!")
}
```

```bash
hugo new posts/my-new-post.md
```

## Related Posts

Scroll to the bottom of this post — you should see a **"You might also like"** section linking back to the first post, since they share the `introduction` tag.