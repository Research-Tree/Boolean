#ReadMe for Boolean
## Code here is for you to use for your social listening projects.  
#### This ReadMe only covers the most basic Boolean arguments. I have only added Brandwatch and YouScan queries here, so consult the Query Operator guide for your platform for any necessary changes.

Every platform uses `AND`, `OR`, and for exclusions some use `NOT`, others use `AND NOT` and still others might also use the minus `-` symbol. (Brandwatch uses both `NOT` and `-`. YouScan also uses `-` and `AND NOT` for exclusion arguments.)

#### Points things to remember:
> When you see curly brackets like `{ }` that means force the search to the desired letter case. That's for Brandwatch only.

> When you see `NEAR/X`, where X is a number, that's a Brandwatch proximity operator for `((word OR "phrases") NEAR/X (word OR "phrases"))` YouScan's proximity operator doesn't require the NEAR term. It's proximity argument is simply `/X`.

> When you see `#`, that is a wildcard operator that will also find any additional iterations of the term either before (when it is leading operator like `#wildcard` OR aftewards when it is a trailing wildcard like `wildcard*`

>> The first example might return "searchforwildcard" and the secondexample could return "wildcardishigh"

> When you see `?`, that means any supported text character would be substituted in its place such as for `organi?ation`

>> That could return either "organisation" or "organization" or perhaps a misspelling.

_ESM_
