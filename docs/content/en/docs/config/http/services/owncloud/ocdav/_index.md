---
title: "ocdav"
linkTitle: "ocdav"
weight: 10
description: >
  Configuration for the OCDav service
---

# _struct: Config_

{{% dir name="insecure" type="bool" default=false %}}
Whether to skip certificate checks when sending requests. [[Ref]](https://github.com/cs3org/reva/tree/master/internal/http/services/owncloud/ocdav/ocdav.go#L113)
{{< highlight toml >}}
[http.services.owncloud.ocdav]
insecure = false
{{< /highlight >}}
{{% /dir %}}

{{% dir name="notifications" type="map[string]interface{}" default=nil %}}
 settings for the notification helper [[Ref]](https://github.com/cs3org/reva/tree/master/internal/http/services/owncloud/ocdav/ocdav.go#L126)
{{< highlight toml >}}
[http.services.owncloud.ocdav]
notifications = nil
{{< /highlight >}}
{{% /dir %}}

