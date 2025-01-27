# LocalTelemetry

Local dashboards for telemetry collection.

## To Use

Clone this repository, and then run:

```
docker-compose up
```

Configure your application to send OpenTelemetry data (traces, logs, and metrics) to `localhost:4317` (the standard/default OTLP endpoint).

Then you will have access to the dasboards below:


[Aspire (logs + traces + metrics)](http://localhost:18888/)

## Persistence

This project uses Docker volumes for persistence; logs and metrics are persisted, as are Grafana dashboard definitions.

Traces are _not_ persisted.

## Contributing

It would be great to have some good Grafana dashboard definitions out of the box.

Also, configuration examples for different languages. I'll get around to doing a .NET one sooner or later.
