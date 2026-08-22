# Kubernetes Services (kubernetes-services)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kubernetes Services provide an abstract way to expose an application running on a set of Pods as a network service. They provide stable networking endpoints and load balancing across pod replicas in a Kubernetes cluster.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Container Orchestration
- Kubernetes
- Load Balancing
- Networking
- Service Discovery

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Kubernetes Services

The Kubernetes Services API provides an abstraction for exposing groups of Pods over a network with a stable virtual IP address and DNS name. It supports ClusterIP, NodePort, LoadBalancer, and ExternalName service types for internal and external connectivity within Kubernetes clusters.

- **Human URL:** [https://kubernetes.io/docs/concepts/services-networking/service/](https://kubernetes.io/docs/concepts/services-networking/service/)

#### Tags

- Kubernetes
- Load Balancing
- Networking
- Service Discovery

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/service/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/service-v1/)
- [OpenAPI](openapi/kubernetes-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kubernetes-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/kubernetes-services-watch-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [JSON Schema](json-schema/kubernetes-services-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Kubernetes Ingress

The Kubernetes Ingress API manages external HTTP and HTTPS access to services within a cluster, providing load balancing, SSL termination, and name-based virtual hosting. Traffic routing is controlled by rules defined on the Ingress resource and fulfilled by an Ingress controller.

- **Human URL:** [https://kubernetes.io/docs/concepts/services-networking/ingress/](https://kubernetes.io/docs/concepts/services-networking/ingress/)

#### Tags

- HTTP
- Kubernetes
- Load Balancing
- Networking

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/ingress/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/ingress-v1/)
- [OpenAPI](openapi/kubernetes-ingress-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kubernetes-ingress.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-ingress.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubernetes Gateway API

The Kubernetes Gateway API is a role-oriented, extensible API for managing ingress and mesh traffic routing in Kubernetes. It supports advanced traffic management including header-based matching, traffic weighting, and multi-protocol routing as a successor to the Ingress API.

- **Human URL:** [https://kubernetes.io/docs/concepts/services-networking/gateway/](https://kubernetes.io/docs/concepts/services-networking/gateway/)

#### Tags

- Gateway
- Kubernetes
- Networking
- Traffic Management

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/gateway/)
- [OpenAPI](openapi/kubernetes-gateway-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kubernetes-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubernetes EndpointSlices

The Kubernetes EndpointSlices API tracks IP addresses, ports, readiness, and topology information for Pods backing a Service. EndpointSlices replaced the older Endpoints API to improve scalability for large clusters and enable topology-aware routing.

- **Human URL:** [https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/](https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/)

#### Tags

- Kubernetes
- Networking
- Service Discovery
- Topology

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/endpoint-slice-v1/)
- [OpenAPI](openapi/kubernetes-endpoint-slices-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kubernetes-endpoint-slices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-endpoint-slices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubernetes Network Policies

The Kubernetes NetworkPolicy API controls how groups of Pods communicate with each other and with external network endpoints. Policies define ingress and egress rules based on Pod selectors, namespace selectors, and IP blocks to implement network segmentation.

- **Human URL:** [https://kubernetes.io/docs/concepts/services-networking/network-policies/](https://kubernetes.io/docs/concepts/services-networking/network-policies/)

#### Tags

- Kubernetes
- Networking
- Policy
- Security

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/network-policies/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/policy-resources/network-policy-v1/)
- [OpenAPI](openapi/kubernetes-network-policies-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kubernetes-network-policies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-network-policies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kubernetes DNS for Services and Pods

Kubernetes provides DNS-based service discovery for Services and Pods within a cluster. DNS records are automatically created for Services, allowing workloads to locate services by name rather than by IP address.

- **Human URL:** [https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)

#### Tags

- DNS
- Kubernetes
- Networking
- Service Discovery

#### Properties

- [Documentation](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)
- [Postman Collection](collections/kubernetes-endpoint-slices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-endpoint-slices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kubernetes-gateway-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-gateway-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kubernetes-ingress.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-ingress.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kubernetes-network-policies.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-network-policies.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/kubernetes-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kubernetes-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://kubernetes.io)
- [Documentation](https://kubernetes.io/docs/concepts/services-networking/)
- [Getting Started](https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/)
- [Reference](https://kubernetes.io/docs/reference/kubernetes-api/service-resources/)
- [GitHub Organization](https://github.com/kubernetes)
- [GitHub Repository](https://github.com/kubernetes/kubernetes)
- [Blog](https://kubernetes.io/blog/)
- [Community](https://kubernetes.io/community/)
- [Changelog](https://kubernetes.io/releases/)
- [JSON Schema](json-schema/kubernetes-services-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/kubernetes-services-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
