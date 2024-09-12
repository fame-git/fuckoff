# Health Check
- Periodically run command /http/tcp/grpc
- Health Check response Good/Not good
- Readiness: Accept client request redirect to healthy pod, ready when all containers within pod are ready
- Liveness:
- Probe gather state: -> Readiness/Liveness probe