
# System Requirements

Before installing ElvioNode, ensure that your infrastructure meets the necessary hardware, software, and network requirements.

ElvioNode is designed to operate on self-hosted infrastructure, ranging from individual virtual private servers to large-scale dedicated server environments.

## Operating System

ElvioNode is designed for Linux-based environments.

### Recommended Distributions

| Distribution | Recommendation |
| --- | --- |
| Ubuntu Server | Recommended |
| Debian | Recommended |

A clean and up-to-date Linux installation is recommended for new deployments.

## Hosting Environment

ElvioNode can be deployed on:

- Virtual Private Servers (VPS)
- Dedicated servers
- Bare-metal infrastructure
- Self-managed physical servers

You must have sufficient administrative privileges to install and configure the required software.

## Hardware Requirements

Hardware requirements depend on the number of game servers, connected nodes, concurrent users, and the workloads being managed.

### Processor

A processor with sufficient computing capacity to handle both the ElvioNode platform and the intended game server workloads.

For performance-sensitive game servers, strong single-threaded CPU performance is recommended.

### Memory

Available system memory must accommodate:

- The operating system.
- ElvioNode services.
- Active game server instances.
- Background processes.
- Additional operational overhead.

Avoid allocating all available system memory to game servers.

### Storage

SSD or NVMe storage is recommended for improved responsiveness and reduced disk latency.

Ensure sufficient storage capacity for:

- Game server installations.
- World data and configurations.
- Plugins and modifications.
- Server logs.
- Backups.
- Future expansion.

Storage requirements vary significantly between games and individual server configurations.

## Software Requirements

ElvioNode requires a compatible Linux environment.

Additional software requirements depend on the games and server software you intend to operate.

### Game-Specific Dependencies

Certain game servers require additional runtime environments or system libraries.

For example, Minecraft Java Edition requires a compatible Java installation.

Always refer to the documentation for your specific game server software when determining its runtime requirements.

## Network Requirements

Your infrastructure should have:

- A stable internet connection.
- Sufficient network bandwidth.
- Access to required software repositories.
- Appropriate firewall configuration.
- Network connectivity between the control panel and connected nodes.

Publicly accessible game servers must have the appropriate game-specific network ports available.

## Domain Name and HTTPS

For production environments, we recommend using a dedicated domain or subdomain for your ElvioNode installation.

Example:

`panel.example.com`

HTTPS is strongly recommended to protect authentication credentials and communication between users and the control panel.

## Multi-Node Environments

When operating multiple nodes, each machine must independently meet the requirements of its assigned workloads.

Consider the following when planning your infrastructure:

- Available CPU and memory resources.
- Storage capacity.
- Network latency between machines.
- Network reliability.
- Geographic location.
- Applicable license limitations.

## Production Recommendations

For commercial hosting providers and larger deployments, we recommend:

- Dedicated infrastructure where appropriate.
- Reliable SSD or NVMe storage.
- Regular operating system security updates.
- Properly configured firewalls.
- HTTPS for publicly accessible services.
- External backup storage.
- Infrastructure monitoring.
- Sufficient resource capacity for future growth.

## Pre-Installation Checklist

Before proceeding with the installation, verify that:

- [ ] A compatible Linux environment is available.
- [ ] Administrative access is available.
- [ ] The operating system is up to date.
- [ ] Sufficient CPU, memory, and storage resources are available.
- [ ] Internet connectivity is available.
- [ ] Required game-specific dependencies are identified.
- [ ] Network and firewall configurations are prepared.
- [ ] A valid ElvioNode license is available.

## Next Steps

Once your infrastructure is prepared, proceed with the installation guide.

---

[Previous: Introduction](introduction.md) · [Return to Documentation](../../README.md)
