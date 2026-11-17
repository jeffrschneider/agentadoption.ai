# agentadoption.ai

Source for https://agentadoption.ai, the Agent Adoption Framework: an open framework for adopting AI agents one department at a time, in four levels (bespoke, activated, orchestrated, self-improving), with the criteria for each level, five sources of agents, the three jobs that move a department up, and five principles. Sponsored by AgentMesh.

The site is static files in the Google Cloud storage bucket `agentadoption-site`, behind the shared `agentcatalog-lb` load balancer. Pushing here publishes nothing. Publish with `tools/publish-site.sh adoption` from the AgentMesh repo, which also writes `sitemap.xml` and `robots.txt` into the bucket.
