# Softlaunch SearXNG host

Private deployment source for the Softlaunch Community Opportunity Engine's
SearXNG search service.

The included Render Blueprint creates a free Docker web service and generates
the SearXNG secret at deployment time. The JSON search API is enabled for the
application's discovery and contact-enrichment jobs.

Render's free service sleeps after 15 minutes without traffic and wakes on the
next request. It is useful for initial validation, but a paid always-on instance
is more appropriate once daily volume becomes business-critical.

