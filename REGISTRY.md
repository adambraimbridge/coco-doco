###Running INSIDE cluster

 - stand alone cluster that includes cache
 - doesn't needs elb/dns/name resolutions
 - no share policies, each gets their own cache


###Running OUTSIDE
- immidiate caching benefits (deployer loaded from cache straight away)
- no need for dependencies in service files
- spinning up new envirnments remains fast

###
v1 vs v2

- V1 failed to download various images based on "FROM golang" and we never understood why.


