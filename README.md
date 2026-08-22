# VPN (vpn)

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

A VPN (Virtual Private Network) creates an encrypted tunnel between a user's device and a remote network, protecting data from interception and masking the user's IP address. VPN technology is widely used for secure remote access to corporate networks, protecting privacy on public Wi-Fi, and bypassing geographic content restrictions. This index documents VPN providers, protocols, and APIs relevant to the VPN technology landscape including NordVPN, OpenVPN, WireGuard, Tailscale, and cloud provider VPN services.

**APIs.json:** [https://en.wikipedia.org/wiki/Virtual_private_network](https://en.wikipedia.org/wiki/Virtual_private_network)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Encryption
- Networking
- Privacy
- Security
- VPN

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### NordVPN API

NordVPN's public API provides server listings, recommendations, and user credential retrieval for programmatic VPN configuration, especially useful for WireGuard (NordLynx) configuration generation.

- **Human URL:** [https://api.nordvpn.com/](https://api.nordvpn.com/)
- **Base URL:** `https://api.nordvpn.com/v1`

#### Tags

- Encryption
- Networking
- Privacy
- Security
- VPN

#### Properties

- [Data Feed](https://api.nordvpn.com/v1/servers)
- [Data Feed](https://api.nordvpn.com/v1/servers/recommendations)
- [Documentation](https://sleeplessbeastie.eu/2019/02/18/how-to-use-public-nordvpn-api/)
- [OpenAPI](openapi/vpn-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vpn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vpn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tailscale API

Tailscale provides a REST API for managing tailnets (private mesh networks), devices, users, access control lists, and network configuration. Built on WireGuard, Tailscale enables zero-configuration VPN for teams and organizations.

- **Human URL:** [https://tailscale.com/api](https://tailscale.com/api)
- **Base URL:** `https://api.tailscale.com/api/v2`

#### Tags

- Encryption
- Mesh Network
- Networking
- Privacy
- Security
- VPN
- WireGuard
- Zero Trust

#### Properties

- [Documentation](https://tailscale.com/api)
- [Base U R L](https://api.tailscale.com/api/v2)
- [Postman Collection](collections/vpn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vpn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AWS VPN API

AWS Site-to-Site VPN and AWS Client VPN provide managed VPN solutions on AWS infrastructure. Managed via the AWS EC2 API and AWS CLI for creating virtual private gateways, customer gateways, and VPN connections.

- **Human URL:** [https://docs.aws.amazon.com/vpn/](https://docs.aws.amazon.com/vpn/)
- **Base URL:** `https://ec2.amazonaws.com/`

#### Tags

- AWS
- Cloud
- Encryption
- Networking
- Security
- VPN

#### Properties

- [Documentation](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html)
- [Documentation](https://docs.aws.amazon.com/vpn/latest/clientvpn-admin/)
- [Postman Collection](collections/vpn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vpn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure VPN Gateway API

Azure VPN Gateway provides managed site-to-site, point-to-site, and VNet-to-VNet VPN connections. Managed via Azure Resource Manager REST API and Azure CLI.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/vpn-gateway/](https://learn.microsoft.com/en-us/azure/vpn-gateway/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Azure
- Cloud
- Encryption
- Networking
- Security
- VPN

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/vpn-gateway/)
- [Documentation](https://learn.microsoft.com/en-us/rest/api/network/vpn-gateways)
- [Postman Collection](collections/vpn.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vpn.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Reference](https://en.wikipedia.org/wiki/Virtual_private_network)
- [Standard](https://www.wireguard.com/)
- [Standard](https://openvpn.net/)
- [Portal](https://tailscale.com/)
- [Website](https://www.nordvpn.com/)
- [Website](https://protonvpn.com/)
- [Open Source](https://github.com/qdm12/gluetun)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
