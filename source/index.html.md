---
title: Portal Network API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - python

toc_footers:
  - <a href='https://portal.network'>Return to Portal Network</a>
#  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to the [Portal Network](https://portal.network) API documentation!  Portal Network provide you an easy access to any Blockchain networks (Bitcoin, Ethereum, and more coming soon). 
You can use our API to access Portal Network API endpoints. The documentation is currently a Work In Progress.

# Authentication

> To authorize, use this code:

```python
import portalnetwork

api = portalnetwork.authorize('auth_key')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: auth_key"
```


> Make sure to replace `auth_key` with your API key.

Portal Network uses API keys to allow access to the API. You can register a new Portal Network API key here (link comiong soon).

Portal Network expects for the API key to be included in all API requests to the server in a header that looks like the following:

`Authorization: auth_key`

<aside class="notice">
You must replace <code>auth_key</code> with your personal API key.
</aside>
