+++
title = "Notice"
description = "A notice box that draws attention to its contents"
+++

A notice box is a highlighted area that draws attention to the content within it. You can get a default style notice by not passing any parameters:
 
 ```
{{</* notice */>}}
This is a default notice.
{{</* /notice */>}}
```
 
 To change the style of the notice, you can pass one of these values in as the 1st parameter:

* `primary`
* `success`
* `warning`
* `danger`

```
{{</* notice "success" */>}}
This is a success notice.
{{</* /notice */>}}
```

## Examples

{{< notice >}}
This is a __default__ notice.
{{< /notice >}}


{{< notice "primary" >}}
This is a __primary__ notice.
{{< /notice >}}


{{< notice "success" >}}
This is a __success__ notice.
{{< /notice >}}


{{< notice "warning" >}}
This is a __success__ notice.
{{< /notice >}}


{{< notice "danger" >}}
This is a __danger__ notice.
{{< /notice >}}