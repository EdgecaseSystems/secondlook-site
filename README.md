# Edgecase SecondLook landing page

Separate static site for SecondLook. It contains no Worker, API, inference, payment, database, analytics, or secret code.

Canonical site: https://secondlook-site.edgecasesystems.workers.dev/
API: https://secondlook.edgecasesystems.workers.dev/

Preview with python3 -m http.server 8080. Cloudflare Workers Builds / Workers Static Assets use GitHub `main` as the
production/public branch, with the repository root as the static asset directory. A push or merge to `main` may
automatically deploy the public site. The canonical public URL is
https://secondlook-site.edgecasesystems.workers.dev/. No custom domain is currently used.
