# ReadMe for Boolean
## Code here is for you to use for your social listening projects.  
#### This ReadMe only covers the most basic Boolean arguments. Consult the query operator guide for your platform for any necessary changes.

Every platform uses `AND`, `OR`, and for exclusions some use `NOT`, others use `AND NOT` and still others might also use the minus `-` symbol. 

#### Points things to remember:
> When you see curly brackets, like `{ }`, that means force the search to return the desired letter case. Check your platform Boolean operator guide to find a similar function if it is supported.

> When you see `NEAR/X`, where X is a number, that's a proximity operator for `((word OR "words or phrases") NEAR/X (word OR "words or phrases"))` Other platforms might use different syntax like only needing '/X' or even 'N/X'. Be sure to check it before you run it.

> The `*`, that is a wildcard operator that will also find any additional iterations of the term, either before the term (when it is leading operator like `*wildcard`), or afterwards when it is a trailing wildcard like `wildcard*`
>> The first example might return "searchforwildcard" and the secondexample could return "wildcardishigh"

> When you see `?`, that means any supported text character would be substituted in its place such as in the example, `organi?ation`
>> That could return either "organisation" or "organization" or, perhaps, a misspelling.

_ESM_
