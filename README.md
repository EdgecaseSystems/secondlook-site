# Edgecase SecondLook landing page

Separate static site for SecondLook. It contains no Worker, API, inference, payment, database, analytics, or secret code.

Canonical site: https://secondlook.edgecasesystems.com/
API: https://secondlook.edgecasesystems.workers.dev/

Preview with python3 -m http.server 8080. Cloudflare Pages should use GitHub main, an empty build command, and the repository root as publish directory. Attach the custom domain only through the Pages custom-domain flow after reviewing DNS separately.
