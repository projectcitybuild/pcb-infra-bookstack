Docker compose stack for running BookStack in production.

This assumes that [pcb-web](https://github.com/projectcitybuild/web) is running in a Docker Compose stack on the same machine, in a network named `pcb-proxy`. This is required, as `pcb-web` provides a reverse proxy, and hands-off requests to BookStack on the `portal.projectcitybuild.com` subdomain.

Be sure to copy and update `.env` for Docker Compose env vars, as well as `config/www/.env` for BookStack env vars.