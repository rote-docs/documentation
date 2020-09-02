+++
title = "Mermaid"
description = "Render Mermaid charts in your site"
+++

The mermaid shortcode is used to embed [Mermaid](http://mermaid-js.github.io/mermaid/#/) charts in your site's pages. To use it, just paste your markup between `{{</* mermaid */>}}...{{</* /mermaid */>}}` tags.

## Examples

{{< notice "primary" >}}
The examples here don't cover every possible chart type. For that, visit [Mermaid's documentation](http://mermaid-js.github.io/mermaid/#/).
{{< /notice >}}

#### Sequence Diagram

```
{{</* mermaid */>}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts<br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{</* /mermaid */>}}
```

{{< mermaid >}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts<br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{< /mermaid >}}

#### Pie Chart

```
{{</* mermaid */>}}
pie title What Voldemort doesn't have?
         "FRIENDS" : 2
         "FAMILY" : 3
         "NOSE" : 45
{{</* /mermaid */>}}
```

{{< mermaid >}}
pie title What Voldemort doesn't have?
         "FRIENDS" : 2
         "FAMILY" : 3
         "NOSE" : 45
{{< /mermaid >}}

#### Flow Chart

```
{{</* mermaid */>}}
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
{{</* /mermaid */>}}
```

{{< mermaid >}}
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
{{< /mermaid >}}