---
layout: default
title: Soda Core usage statistics
description: To understand how users are using Soda Core, the Soda dev team added telemetry event tracking to Soda Core. See instructions to opt-out.
parent: Reference
---

# Soda Core usage statistics

To understand how users are using Soda Core, and to proactively capture bugs and performance issues, the Soda development team has added telemetry event tracking to Soda Core. 

Soda tracks usage statistics using the Open Telemetry Framework. The data Soda tracks is completely anonymous, does not contain any personally identifiying information (PII) in any form, and is purely for internal use.

## Opt out of usage statistics

Soda Core collects usage statistics by default. You can opt-out from sending Soda Core usage statistics at any time by adding the following to your `~/.soda/config.yml` file:
```
send_anonymous_usage_stats: false
```

## Go further

* Learn [How Soda Core works]({% link soda-core/how-core-works.md %}).
* Need help? Join the <a href="http://community.soda.io/slack" target="_blank"> Soda community on Slack</a>.

<br />

---
{% include docs-footer.md %}