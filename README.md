# Zenth VPN Server

**Zenth VPN Server** is a secure, scalable, and open-source VPN solution developed by Sky Genesis Enterprise for the Zenth Cloud ecosystem. It provides encrypted remote access, site-to-site connectivity, and integrates seamlessly with Zenth’s network and identity services.

## 🔐 Features

- ✅ Supports OpenVPN, WireGuard, and IPsec protocols
- ✅ User authentication via `ldap-server` (SSO ready)
- ✅ Centralized configuration via `api-server`
- ✅ Dynamic IP assignment with `dhcp-server` integration
- ✅ Role-based access control and policy enforcement
- ✅ Real-time status and metrics available via `status-server`
- ✅ Containerized deployment (Docker, Kubernetes, Proxmox)
- ✅ Supports multi-tenant environments

## 📦 Part of the Zenth Cloud Stack

Zenth VPN Server interacts closely with:

- `ldap-server` – User and group authentication
- `api-server` – Configuration and orchestration
- `dhcp-server` – IP address allocation
- `firewall-server` – Access control and routing policies
- `status-server` – Monitoring and alerting
- `panel-server` – Administration and user management

## 🛠️ Technology

- Built on top of proven open-source VPN technologies (WireGuard, OpenVPN)
- Modern Go-based backend for orchestration and API integration
- Supports automatic certificate management and renewal
- Designed for high availability and scalability

## 📖 Documentation

Detailed setup guides, configuration options, and API references are available in `/docs` or on [Documentations](https://docs.zenthcloud.com).

## 🛡️ License

Zenth VPN Server is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. See the `LICENSE` file for full terms.

---

Contributions, bug reports, and feature requests are welcome at [github.com/zenthcloud](https://github.com/zenthcloud).
