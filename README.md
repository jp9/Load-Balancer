Load-Balancer
=============

Load balancer reference implementation. Important features:
- A simplistic load balancer implementation
- A request is always routed to the same server.
- Differentiating feature: The web servers are started/stopped/paused on demand.
    - For example: The webserver do not need to be started at all. Only when the first request arrives, the web server is started
    on demand (if there are no requests for some time, then the web servers will be hibernated/shutdown).
- Start/Stop/hibernate scripts have to be provided as part of the configuration.
- Implemented in Javascript and is very light weight.
- DONOT USE IN PRODUCTION
- PROVIDED AS IS.
