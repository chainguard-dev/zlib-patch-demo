# zlib-patch-demo

This is a demonstration of Melange's patch action, as well as how security fixes
are recorded for the VEX feed.

In [commit 951cbb3][c-1], a vulnerable package, zlib-1.2.11-r0 is built.  It is vulnerable
to CVE-2018-25032.

In [commit 4a77126][c-2], we apply an upstream mitigation to resolve CVE-2018-25032.

   [c-1]: https://github.com/chainguard-dev/zlib-patch-demo/commit/951cbb3beba397380f4216c990774d3de05fd4db
   [c-2]: https://github.com/chainguard-dev/zlib-patch-demo/commit/4a7712677558c73940f73a4c648cc00db8aa1d55
