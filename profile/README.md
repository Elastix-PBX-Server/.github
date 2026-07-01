# Elastix Unified Communications Server for Windows

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Isotipo-elastix.png" alt="Elastix Unified Communications Server" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/Elastix-PBX-Server)

---

## What is Elastix?

Elastix is an open-source unified communications server software that brings together IP PBX, email, instant messaging, and fax capabilities in a single, integrated platform [citation:9]. It combines the power of Asterisk PBX with a user-friendly web interface, making it accessible for both small businesses and enterprise deployments. The platform provides a complete telephony solution with VoIP support, call center features, and extensive integration options.

Infrastructure teams managing voice communications benefit from Elastix's comprehensive feature set and modular architecture. System administrators appreciate the web-based administration interface that simplifies PBX management, call routing, and extension provisioning. The platform supports multiple codecs, SIP trunks, and integration with external telephony providers.

---

## Screenshot Block

<div align="center">
  <img src="https://a.fsdn.com/con/app/proj/elastix/screenshots/321531.jpg/max/max/1" alt="Elastix PBX Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/Elastix-PBX-Server)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **IP PBX** | Full-featured PBX with extension management, call routing, IVR, and voicemail capabilities |
| **VoIP Support** | SIP and IAX2 protocols, codec support, and trunk management for voice over IP |
| **Unified Communications** | Integration of email, instant messaging, fax, and voice in a single platform |
| **Web-Based Administration** | User-friendly web interface for PBX configuration and management |
| **Call Center Features** | Queue management, agent monitoring, call recording, and reporting |
| **Video Conferencing** | Built-in video conferencing capabilities for remote collaboration |
| **Fax Server** | Integrated fax support with virtual fax reception and sending |
| **Email Integration** | Email to fax and fax to email capabilities |
| **CRM Integration** | Support for integration with SugarCRM and other CRM platforms |
| **Security** | TLS and SRTP encryption, firewall integration, and intrusion detection |
| **Reporting** | Call detail records (CDR), real-time statistics, and customizable reports |
| **Multi-Language** | Support for multiple languages in the web interface |

---

## Installation Guide

### Prerequisites

- Virtual machine with Hyper-V, VMware, or VirtualBox
- Minimum 2 GB RAM, 2 CPU cores
- 20 GB available disk space
- Network connectivity

### Step 1: Download Elastix

The latest version of Elastix is available from the official website or GitHub repository.

### Step 2: Set Up Virtual Machine

**Step 1:** Create a new virtual machine in Hyper-V, VMware, or VirtualBox.

**Step 2:** Allocate recommended resources:
- RAM: Minimum 2 GB (4 GB recommended)
- CPU: 2 cores
- Storage: 20 GB (expandable for CDR and recording storage)

**Step 3:** Mount the Elastix ISO and boot from it.

### Step 3: Install Elastix

**Step 1:** Boot from the installation media and select **Install** .

**Step 2:** Follow the installation wizard:
- Select the language and keyboard layout
- Set the partition scheme (use entire disk or custom partition)
- Set the root password
- Configure network settings

**Step 3:** When the installation is complete, remove the installation media and restart the system.

### Step 4: Post-Installation Configuration

**Step 1:** Access the web administration interface:
- Open browser and navigate to `https://<server-ip>/admin`
- The default username is `admin` and password is the one you set during installation

**Step 2:** Configure the time zone, language, and email settings in System > General Settings.

**Step 3:** Add SIP trunks to connect to external telephony providers.

**Step 4:** Create extensions for internal users.

**Step 5:** Create IVR menus and call queues as needed.

**Step 6:** Configure call recording settings under PBX > Call Recording.

**Step 7:** For fax capabilities, configure the virtual fax extension.

---

## Usage

### Accessing Web Interfaces

- Administration Panel: `https://<server-ip>/admin`
- User Panel: `https://<server-ip>/user`
- Email: `https://<server-ip>/roundcube` or `https://<server-ip>/squirrelmail`

### System Updates

**Step 1:** Access the administration panel.

**Step 2:** Navigate to System > Updates.

**Step 3:** Check for available updates and apply them as needed.

### Backup and Restore

**Step 1:** Navigate to System > Backup/Restore.

**Step 2:** Create a backup including PBX configuration, CDR database, and recordings.

**Step 3:** Store backups in a secure location.

---

## System Requirements

| Component | Minimum Specification | Recommended Specification |
|-----------|----------------------|--------------------------|
| Operating System | Virtual machine with Windows host | Virtual machine with Windows host |
| CPU | 2 cores | 4+ cores |
| RAM | 2 GB | 4 GB |
| Storage | 20 GB | 50 GB (expandable) |
| Network | 100 Mbps | 1 Gbps |
| Virtualization | Hyper-V, VMware, VirtualBox | Hyper-V, VMware, VirtualBox |
| Licenses | Open source (free) | Commercial support available |

---

## Keywords

Elastix • PBX • VoIP • Unified Communications • Asterisk • Call Center • IP PBX • SIP • IAX2 • Fax Server • Video Conferencing • Open Source • Telephony • Business Communications • Phone System • Call Queues • IVR • Call Recording • CRM Integration • Email Integration • Issabel • Linux PBX • Virtual PBX • Enterprise Telephony • Small Business PBX
