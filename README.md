Uptime Robot jquery plugin
===========

jquery plugin for showing your uptime robot monitors

Dependencies
===========
* jquery
* underscore.js

Configuration
===========

Initialize by:

```
$("body").uptimeRobot({monitorConfs: [
    {
     	apiKey: "XXX",
        name: "displayName",
        location : "displayLocayion"
    }],
    containerId: "monitors",
    monitorTemplateId: "monitor_template"
});
```

Where 'monitors' is the container element the monitors will be appended to, and 'monitor_template' is the underscore template used to draw each monitor.

