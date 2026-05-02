# Kubernetes Services (kubernetes-services)
Kubernetes Services provide an abstract way to expose an application running on a set of Pods as a network service. They provide stable networking endpoints and load balancing across pod replicas in a Kubernetes cluster.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Kubernetes, Container Orchestration, Networking, Load Balancing, Service Discovery

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-04-28 

## APIs

### Kubernetes Services
The Kubernetes Services API provides an abstraction for exposing groups of Pods over a network with a stable virtual IP address and DNS name. It supports ClusterIP, NodePort, LoadBalancer, and ExternalName service types for internal and external connectivity within Kubernetes clusters.

**Human URL:** [https://kubernetes.io/docs/concepts/services-networking/service/](https://kubernetes.io/docs/concepts/services-networking/service/)


#### Tags:

 - Kubernetes, Networking, Load Balancing, Service Discovery

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/service/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/service-v1/)
- [OpenAPI](openapi/kubernetes-services-openapi.yml)
- [AsyncAPI](asyncapi/kubernetes-services-watch-asyncapi.yml)
- [JSONSchema](json-schema/kubernetes-services-schema.json)

### Kubernetes Ingress
The Kubernetes Ingress API manages external HTTP and HTTPS access to services within a cluster, providing load balancing, SSL termination, and name-based virtual hosting. Traffic routing is controlled by rules defined on the Ingress resource and fulfilled by an Ingress controller.

**Human URL:** [https://kubernetes.io/docs/concepts/services-networking/ingress/](https://kubernetes.io/docs/concepts/services-networking/ingress/)


#### Tags:

 - Kubernetes, Networking, HTTP, Load Balancing

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/ingress/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/ingress-v1/)
- [OpenAPI](openapi/kubernetes-ingress-openapi.yml)

### Kubernetes Gateway API
The Kubernetes Gateway API is a role-oriented, extensible API for managing ingress and mesh traffic routing in Kubernetes. It supports advanced traffic management including header-based matching, traffic weighting, and multi-protocol routing as a successor to the Ingress API.

**Human URL:** [https://kubernetes.io/docs/concepts/services-networking/gateway/](https://kubernetes.io/docs/concepts/services-networking/gateway/)


#### Tags:

 - Kubernetes, Networking, Gateway, Traffic Management

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/gateway/)
- [OpenAPI](openapi/kubernetes-gateway-api-openapi.yml)

### Kubernetes EndpointSlices
The Kubernetes EndpointSlices API tracks IP addresses, ports, readiness, and topology information for Pods backing a Service. EndpointSlices replaced the older Endpoints API to improve scalability for large clusters and enable topology-aware routing.

**Human URL:** [https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/](https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/)


#### Tags:

 - Kubernetes, Networking, Service Discovery, Topology

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/endpoint-slice-v1/)
- [OpenAPI](openapi/kubernetes-endpoint-slices-openapi.yml)

### Kubernetes Network Policies
The Kubernetes NetworkPolicy API controls how groups of Pods communicate with each other and with external network endpoints. Policies define ingress and egress rules based on Pod selectors, namespace selectors, and IP blocks to implement network segmentation.

**Human URL:** [https://kubernetes.io/docs/concepts/services-networking/network-policies/](https://kubernetes.io/docs/concepts/services-networking/network-policies/)


#### Tags:

 - Kubernetes, Networking, Security, Policy

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/policy-resources/network-policy-v1/)
- [OpenAPI](openapi/kubernetes-network-policies-openapi.yml)

### Kubernetes DNS for Services and Pods
Kubernetes provides DNS-based service discovery for Services and Pods within a cluster. DNS records are automatically created for Services, allowing workloads to locate services by name rather than by IP address.

**Human URL:** [https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)


#### Tags:

 - Kubernetes, Networking, DNS, Service Discovery

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)

## Common Properties

- [Website](https://kubernetes.io)
- [Documentation](https://kubernetes.io/docs/concepts/services-networking/)
- [Getting Started](https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/)
- [GitHub Organization](https://github.com/kubernetes)
- [GitHubRepository](https://github.com/kubernetes/kubernetes)
- [Blog](https://kubernetes.io/blog/)
- [Community](https://kubernetes.io/community/)
- [Change Log](https://kubernetes.io/releases/)
- [JSONSchema](json-schema/kubernetes-services-schema.json)
- [JSON-LD](json-ld/kubernetes-services-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
