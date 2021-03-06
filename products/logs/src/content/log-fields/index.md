---
title: Log fields
order: 50
---

import LogFieldsHTTPRequests from "./_partials/http_requests"
import LogFieldsSpectrumEvents from "./_partials/spectrum_events"
import LogFieldsFirewallEvents from "./_partials/firewall_events"

# Log fields

The tables below describe the fields available by log category. The list of fields is also accessible directly from the API:
`https://api.cloudflare.com/client/v4/zones/<zone_id>/logpush/datasets/<dataset>/fields`, where the `dataset` argument indicates the log category (either `http_requests`, `spectrum_events`, or `firewall_events`).

## HTTP requests

<TableWrap>

<LogFieldsHTTPRequests/>

</TableWrap>


## Spectrum events

<TableWrap>

<LogFieldsSpectrumEvents/>

</TableWrap>


## Firewall events

<TableWrap>

<LogFieldsFirewallEvents/>

</TableWrap>
