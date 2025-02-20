---
title: "TravisCI"
date: 2018-07-18T14:36:08-04:00
draft: false
weight: 240
---

<img class="screenshot" src="/imgs/modules/travisci.png" width="640" height="187" alt="travisci screenshot" />

Displays build information for your Travis CI account.

## Configuration

```yaml
travisci:
  apiKey: "3276d7155dd9ee27b8b14f8743a408a9"
  enabled: true
  position:
    top: 4
    left: 1
    height: 1
    width: 2
  pro: false
  refreshInterval: 900
```

{{% attributes %}}
  {{< attributes/apikey name="TravisCI" link="https://developer.travis-ci.org/authentication" >}}
  {{< attributes/border >}}
  {{< attributes/enabled >}}
  {{< attributes/focusChar >}}
  {{< attributes/position >}}
  {{< attributes/custom name="pro" desc="Determines whether or not this module will use the Pro version of Travis CI." value="true, false" >}}
  {{< attributes/refreshInterval >}}
{{% /attributes %}}

{{% keyboard %}}
  {{< keyboard/foreSlash >}}
  {{< keyboard/return desc="Open the selected build in the browser" >}}

  {{< keyboard/spacer >}}

  {{< keyboard/j >}}
  {{< keyboard/k >}}
  {{< keyboard/r >}}

  {{< keyboard/spacer >}}

  {{< keyboard/arrowDown >}}
  {{< keyboard/arrowUp >}}

{{% /keyboard %}}

{{% sourcePath module="travisci" %}}