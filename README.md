# VPN (vpn)

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
