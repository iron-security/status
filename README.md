# status.iron.security

The status monitoring website of IRON that checks uptime for various critical services such as the public website.

This is based on the excellent work of [eidam/cf-workers-status-page](https://github.com/eidam/cf-workers-status-page).

[Cloudflare Workers](https://workers.cloudflare.com) was chosen to allow us to run out own status page in two parts:

- The [Flareact](https://flareact.com/) (edge-rendered React) frontend and API of our status page
- The uptime monitors which run on the Cloudflare edge 

## Development

```shell
% wrangler dev
```
