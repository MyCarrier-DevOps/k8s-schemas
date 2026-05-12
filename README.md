# k8s-schemas

JSON Schema definitions for custom Kubernetes resources used at MyCarrier.

## Schemas

### [`gateway.krakend.io`](schemas/gateway.krakend.io/) (v1alpha1)
- [KrakenDGateway](schemas/gateway.krakend.io/krakendgateway_v1alpha1.json)
- [KrakenDEndpoint](schemas/gateway.krakend.io/krakendendpoint_v1alpha1.json)
- [KrakenDBackendPolicy](schemas/gateway.krakend.io/krakendbackendpolicy_v1alpha1.json)
- [KrakenDAutoConfig](schemas/gateway.krakend.io/krakendautoconfig_v1alpha1.json)

### [`offload.mycarrier.dev`](schemas/offload.mycarrier.dev/) (v1alpha1)
- [OffloadBase](schemas/offload.mycarrier.dev/offloadbase_v1alpha1.json) — base service identity for offload routing
- [OffloadRoute](schemas/offload.mycarrier.dev/offloadroute_v1alpha1.json) — per-feature claim on a service

## Layout

```
schemas/<group>/<kind>_<version>.json
```

All schemas conform to JSON Schema draft-07.
