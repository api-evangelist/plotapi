# PlotAPI (plotapi)

Automotive and property data API — US VIN histories and vehicle specifications, UK MOT records,
auto parts fitment, valuations, and UK/US property listings, served as typed JSON over a single
REST endpoint.

**APIs.json:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/plotapi/refs/heads/main/apis.yml)

- **Website:** https://plotapi.co
- **Documentation:** https://plotapi.co/dashboard/docs (account required)

Part of the [API Evangelist](https://apievangelist.com) network.

## Why this entry is thin

Submitted through the apis.io Add-API form on 2026-08-19 and listed by hand. The company is real
and the API is live — this is a valid provider, and a thin entry with a low score is the honest
result rather than a reason to withhold the listing.

The interface is what is not public. `plotapi.co/dashboard/docs` returns 200 but carries only
1,090 bytes of visible text and six sign-in prompts — an account wall, not documentation. `/docs`,
`/api-reference` and `/pricing` all return 404. No operation, parameter, response shape, rate limit
or price is readable without an account, which is why this entry records a single undescribed API
rather than an operation inventory.

Three machine-readable files are advertised and not served: the submitted `apis.json`, plus
`openapi.json` and `llms.txt` linked in the site footer. Each returns exactly 11,358 bytes — the
same response as an invented control path — with both a default and a browser user-agent, so this
is not bot filtering hiding them.

Nothing in this repo is derived or modelled. No operations are asserted because none are readable.
