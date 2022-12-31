FROM temporalio/web:1.18.5

ENTRYPOINT ["/bin/sh", "-c", "TEMPORAL_GRPC_ENDPOINT=$TEMPORAL_GRPC_HOST:7233 node server.js"]
