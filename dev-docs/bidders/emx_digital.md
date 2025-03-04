---
layout: bidder
title: EMX Digital
description: Prebid EMX Digital Bidder Adaptor
pbjs: true
pbs: true
biddercode: emx_digital
media_types: banner, video
gdpr_supported: true
gvl_id: 183
usp_supported: true
schain_supported: true
floors_supported: true
userIds: identityLink, uid2
sidebarType: 1
---

{: .alert.alert-warning :}
The emx_digital bidder is deprecated, and will be removed in a future release of Prebid.js and Prebid Server.

### Registration

To use this bidder you will need an account and a valid tagid from our exchange.  For further information, please contact your Account Manager or adops@emxdigital.com.

### Bid Params

{: .table .table-bordered .table-striped }
| Name              | Scope    | Description                                                                                                          | Example                                       | Type       |
|-------------------|----------|----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|------------|
| `tagid`           | required | The Tag ID from EMX Digital.                                                                                         | `test1`                                       | `string`   |
| `bidfloor`        | optional | The CPM bid floor                                                                                                    | `0.25`                                        | `string`   |
