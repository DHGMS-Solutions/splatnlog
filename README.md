# splatlog4net

Simple Integration of Splat logging to NLog. Based on upon old code for ReactiveUI for logging to NLog which is now no longer in Splat or ReactiveUI

## Getting started

Configure NLog via any method you wish to use (Config File, Code based, etc.).

During program initialisation use:

```cs
Splat.NLog.Helpers.UseNLog()
```

Then use IEnableLogger as described in the main Splat project https://github.com/paulcbetts/splat/blob/master/README.md#logging

