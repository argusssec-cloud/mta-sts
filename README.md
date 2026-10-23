# mta-sts.argussec.net

Serves the [MTA-STS](https://datatracker.ietf.org/doc/html/rfc8461) policy for
`argussec.net` from GitHub Pages at `https://mta-sts.argussec.net/.well-known/mta-sts.txt`.

To change the policy: edit `.well-known/mta-sts.txt`, then bump the `id` in the
`_mta-sts.argussec.net` TXT record so receivers refetch it.
