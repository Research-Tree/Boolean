#ReadMe for Boolean
## Code here is for your social listening projects.  
#### This ReadMe only covers the most basic Boolean arguments. Specifications of Boolean vary by platform, so consult the Query Operator guide for your platform.

Every platform uses `AND`, `OR`, and with exclusions some use `NOT`, others use `AND NOT` and still others might also use the minus `-` symbol.

#### Points things to remember:
> When you see `NEAR/X`, where X is a number, that's a proximity operator for `((word OR "phrases made of words") NEAR/X (word OR "phrases made of words"))` 

> When you see `*`, that is a wildcard operator that will also find any additional iterations of the term either before (when it is leading operator like `*wildcard` OR aftewards when it is a trailing wildcard like `wildcard*` 

>> The first example might return "searchforwildcard" and the secondexample could return "wildcardishigh"

>>> Most platforms support trailing wildcards, often with limits on now often they can be used within a given query. Fewer support leading wildcards.

> When you see `?`, that means any supported text character would be substituted in its place such as for `organi?ation`

>> That could return either "organisation" or "organization" or another misspelling.

_ESM_
