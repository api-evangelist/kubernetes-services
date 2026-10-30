# Kubernetes Services

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

**Areas:** Container Orchestration · Kubernetes · Load Balancing · Networking · Service Discovery

## Kubernetes Services on APIs.io

Everything profiled for Kubernetes Services is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kubernetes-services/](https://apis.io/providers/kubernetes-services/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Kubernetes DNS for Services and Pods](https://apis.io/apis/kubernetes-services/kubernetes-dns/) — Kubernetes provides DNS-based service discovery for Services and Pods within a cluster. DNS records are automatically created for Services, allowing…
- [Kubernetes Services EndpointSlices API](https://apis.io/apis/kubernetes-services/kubernetes-services-endpointslices-api/) — EndpointSlice resources tracking IP addresses, ports, and readiness of pods backing a Service, with topology-aware routing support.
- [Kubernetes Services Gateway API](https://apis.io/apis/kubernetes-services/kubernetes-services-gateway-api/) — Gateway resources instantiating traffic-handling infrastructure such as cloud load balancers or in-cluster proxies, with listeners for each protocol.
- [Kubernetes Services GatewayClass API](https://apis.io/apis/kubernetes-services/kubernetes-services-gatewayclass-api/) — GatewayClass resources defining a class of gateway implementations. Cluster-scoped resources that link to a specific ingress or mesh controller.
- [Kubernetes Services GRPCRoute API](https://apis.io/apis/kubernetes-services/kubernetes-services-grpcroute-api/) — GRPCRoute resources defining gRPC routing rules from Gateway listeners to backend services with service and method name matching.
- [Kubernetes Services HTTPRoute API](https://apis.io/apis/kubernetes-services/kubernetes-services-httproute-api/) — HTTPRoute resources defining HTTP and HTTPS routing rules from Gateway listeners to backend services with support for path, header, and query parameter…
- [Kubernetes Services Ingress API](https://apis.io/apis/kubernetes-services/kubernetes-services-ingress-api/) — Ingress resources defining HTTP and HTTPS routing rules from external traffic to cluster services, with TLS termination support.
- [Kubernetes Services IngressClass API](https://apis.io/apis/kubernetes-services/kubernetes-services-ingressclass-api/) — IngressClass resources identifying which ingress controller should fulfill an Ingress resource.
- [Kubernetes Services IngressStatus API](https://apis.io/apis/kubernetes-services/kubernetes-services-ingressstatus-api/) — Status subresource for Ingress objects, reporting load balancer IP or hostname assignments from the ingress controller.
- [Kubernetes Services Namespaces API](https://apis.io/apis/kubernetes-services/kubernetes-services-namespaces-api/) — The Namespaces API from Kubernetes Services — 2 operation(s) for namespaces.
- [Kubernetes Services API](https://apis.io/apis/kubernetes-services/kubernetes-services-services-api/) — The Services API from Kubernetes Services — 1 operation(s) for services.
- [Kubernetes Services Network Policy API](https://apis.io/apis/kubernetes-services/kubernetes-services-network-policy-api/) — NetworkPolicy resources controlling Pod-level traffic ingress and egress based on label selectors, namespace selectors, and IP CIDR blocks.
- [Kubernetes Services Service Status API](https://apis.io/apis/kubernetes-services/kubernetes-services-service-status-api/) — Status subresource operations for Services, used to update load balancer provisioning state and conditions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Kubernetes Services Watch Events](https://apis.io/asyncapis/kubernetes-services/kubernetes-services-watch-asyncapi/)

#### Event channels (7)

Individual events and webhooks the provider emits.

- [/api/v1/namespaces/{namespace}/services](https://apis.io/channels/kubernetes-services/api-v1-namespaces-namespace-services/)
- [/api/v1/services](https://apis.io/channels/kubernetes-services/api-v1-services/)
- [/apis/discovery.k8s.io/v1/namespaces/{namespace}/endpointslices](https://apis.io/channels/kubernetes-services/apis-discovery-k8s-io-v1-namespaces-namespace-endpointslices/)
- [/apis/gateway.networking.k8s.io/v1/namespaces/{namespace}/gateways](https://apis.io/channels/kubernetes-services/apis-gateway-networking-k8s-io-v1-namespaces-namespace-gateways/)
- [/apis/gateway.networking.k8s.io/v1/namespaces/{namespace}/httproutes](https://apis.io/channels/kubernetes-services/apis-gateway-networking-k8s-io-v1-namespaces-namespace-httproutes/)
- [/apis/networking.k8s.io/v1/namespaces/{namespace}/ingresses](https://apis.io/channels/kubernetes-services/apis-networking-k8s-io-v1-namespaces-namespace-ingresses/)
- [/apis/networking.k8s.io/v1/namespaces/{namespace}/networkpolicies](https://apis.io/channels/kubernetes-services/apis-networking-k8s-io-v1-namespaces-namespace-networkpolicies/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Kubernetes Services Agentic Access](https://apis.io/agentic-access/kubernetes-services/kubernetes-services-agentic-access/)

#### JSON Schema (47)

The data models the API reads and writes.

- [Kubernetes Services Resource](https://apis.io/schemas/kubernetes-services/kubernetes-services/)
- [Condition](https://apis.io/schemas/kubernetes-services/kubernetes-services-condition/)
- [Endpoint](https://apis.io/schemas/kubernetes-services/kubernetes-services-endpoint/)
- [EndpointConditions](https://apis.io/schemas/kubernetes-services/kubernetes-services-endpointconditions/)
- [EndpointHints](https://apis.io/schemas/kubernetes-services/kubernetes-services-endpointhints/)
- [EndpointPort](https://apis.io/schemas/kubernetes-services/kubernetes-services-endpointport/)
- [EndpointSlice](https://apis.io/schemas/kubernetes-services/kubernetes-services-endpointslice/)
- [EndpointSliceList](https://apis.io/schemas/kubernetes-services/kubernetes-services-endpointslicelist/)
- [Gateway](https://apis.io/schemas/kubernetes-services/kubernetes-services-gateway/)
- [GatewayClass](https://apis.io/schemas/kubernetes-services/kubernetes-services-gatewayclass/)
- [GatewayClassList](https://apis.io/schemas/kubernetes-services/kubernetes-services-gatewayclasslist/)
- [GatewayList](https://apis.io/schemas/kubernetes-services/kubernetes-services-gatewaylist/)
- [GatewayListener](https://apis.io/schemas/kubernetes-services/kubernetes-services-gatewaylistener/)
- [GRPCRoute](https://apis.io/schemas/kubernetes-services/kubernetes-services-grpcroute/)
- [GRPCRouteList](https://apis.io/schemas/kubernetes-services/kubernetes-services-grpcroutelist/)
- [HTTPBackendRef](https://apis.io/schemas/kubernetes-services/kubernetes-services-httpbackendref/)
- [HTTPIngressPath](https://apis.io/schemas/kubernetes-services/kubernetes-services-httpingresspath/)
- [HTTPRoute](https://apis.io/schemas/kubernetes-services/kubernetes-services-httproute/)
- [HTTPRouteList](https://apis.io/schemas/kubernetes-services/kubernetes-services-httproutelist/)
- [HTTPRouteMatch](https://apis.io/schemas/kubernetes-services/kubernetes-services-httproutematch/)
- [Ingress](https://apis.io/schemas/kubernetes-services/kubernetes-services-ingress/)
- [IngressBackend](https://apis.io/schemas/kubernetes-services/kubernetes-services-ingressbackend/)
- [IngressClass](https://apis.io/schemas/kubernetes-services/kubernetes-services-ingressclass/)
- [IngressClassList](https://apis.io/schemas/kubernetes-services/kubernetes-services-ingressclasslist/)
- [IngressList](https://apis.io/schemas/kubernetes-services/kubernetes-services-ingresslist/)
- …and 22 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Kubernetes Services Structure](https://apis.io/json-structure/kubernetes-services/kubernetes-services-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Kubernetes Services Context](https://apis.io/jsonld/kubernetes-services/kubernetes-services-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Kubernetes Services Domain Vocabulary](https://apis.io/vocabularies/kubernetes-services/kubernetes-services-vocabulary/)

#### Collections (17)

Postman and Open Collection request collections.

- [Kubernetes Services Kubernetes EndpointSlices API](https://apis.io/collections/kubernetes-services/open-kubernetes-endpoint-slices/)
- [Kubernetes Services Kubernetes Gateway API](https://apis.io/collections/kubernetes-services/open-kubernetes-gateway-api/)
- [Kubernetes Services Kubernetes Ingress API](https://apis.io/collections/kubernetes-services/open-kubernetes-ingress/)
- [Kubernetes Services Kubernetes Network Policies API](https://apis.io/collections/kubernetes-services/open-kubernetes-network-policies/)
- [Kubernetes Services API](https://apis.io/collections/kubernetes-services/open-kubernetes-services/)
- [Kubernetes Services Kubernetes EndpointSlices API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-endpointslices-api/)
- [Kubernetes Services Kubernetes EndpointSlices Gateway API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-gateway-api/)
- [Kubernetes Services Kubernetes EndpointSlices GatewayClass API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-gatewayclass-api/)
- [Kubernetes Services Kubernetes EndpointSlices GRPCRoute API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-grpcroute-api/)
- [Kubernetes Services Kubernetes EndpointSlices HTTPRoute API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-httproute-api/)
- [Kubernetes Services Kubernetes EndpointSlices Ingress API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-ingress-api/)
- [Kubernetes Services Kubernetes EndpointSlices IngressClass API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-ingressclass-api/)
- [Kubernetes Services Kubernetes EndpointSlices IngressStatus API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-ingressstatus-api/)
- [Kubernetes Services Kubernetes EndpointSlices Namespaces API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-namespaces-api/)
- [Kubernetes Services Kubernetes EndpointSlices NetworkPolicy API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-networkpolicy-api/)
- [Kubernetes Kubernetes EndpointSlices Services API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-services-api/)
- [Kubernetes Services Kubernetes EndpointSlices ServiceStatus API](https://apis.io/collections/kubernetes-services/open-kubernetes-services-servicestatus-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Kubernetes Services — asyncapi rules](https://apis.io/rules/kubernetes-services/kubernetes-services-asyncapi-spectral-rules/)
- [Kubernetes Services — jsonschema rules](https://apis.io/rules/kubernetes-services/kubernetes-services-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Kubernetes Services Authentication](https://apis.io/security/kubernetes-services/kubernetes-services-authentication/)
- [Kubernetes Services Domain Security](https://apis.io/security/kubernetes-services/kubernetes-services-domain-security/)
- [Kubernetes Services Vulnerability Disclosure](https://apis.io/security/kubernetes-services/kubernetes-services-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kubernetes Services Plans Pricing](https://apis.io/plans/kubernetes-services/kubernetes-services-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kubernetes Services Rate Limits](https://apis.io/rate-limits/kubernetes-services/kubernetes-services-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kubernetes Services Finops](https://apis.io/finops/kubernetes-services/kubernetes-services-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://kubernetes.io)
- [Documentation](https://kubernetes.io/docs/concepts/services-networking/)
- [Getting started](https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/)
- [Changelog](https://kubernetes.io/releases/)
- [Blog](https://kubernetes.io/blog/)
- [GitHub](https://github.com/kubernetes)

## API Evangelist rating

**Kin Score 41.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 66.6 |
| Contract governance | 13.6 |
| Operational transparency | 34.2 |
| Developer ergonomics | 45.2 |
| Access clarity | 5.3 |

**Agent readiness 30.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bound |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kubernetes-services/](https://apis.io/providers/kubernetes-services/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kubernetes Services: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kubernetes-services/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
