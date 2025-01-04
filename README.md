# DevOps Engineer - Stack

### ☁️ Infrastructure & Cloud
- Amazon Web Services, Microsoft Azure
- Terraform/OpenTofu, Ansible, Pulimi, Packer
- NixOS, Debian/Ubuntu, Fedora/Silverblue/CentOS/RHEL, OpenSUSE, Arch/Artix, Void, Windows

### 🚀 Containers & Orchestration
- Kubernetes: EKS/AKS, RKE2/k3s
- Docker, Podman
- Helm Charts
- NGINX Ingress
- GitOps practices: ArgoCD, Rancher
- QEMU/KVM, VirtualBox, Distrobox

### 🔄 CI/CD & Security
- GitHub Actions, GitLab CI
- HashiCorp Vault, Mozilla SOPS, AWS Secret Manager/Azure Key Vault
- Trivy, SysDig, SonarQube, Qualys
- AppArmor, SELinux, iptables
- OpenVPN, WireGuard

### 📊 Monitoring & Backup

- PLG Stack: Grafana + Prometheus + Loki + Promtail
- ELK Stack: Kibana + ElasticSearch + Logstash + Filebeat
- Falco
- Velero
- Veeam
- Wireshark

### 🏆 Certifications
- Certified Kubernetes: Security Specialist - CKS
- Certified Kubernetes: Application Developer - CKAD
- Certified Kubernetes: Administrator - CKA
- Linux Foundation: System Administrator - LFCS
- HashiCorp: Terraform - Associate 003
- Microsoft Azure Fundamentals AZ-900
- AWS: Solution Architect - Associate
- AWS: Cloud Practitioner


### 📫 Contact
- Email: aleks.safronov@proton.me
- GitHub: thejondaw
- Location: Chicago, IL

---

# My ThinkPad T14 Gen 4

### 🗄️ Core System
- NixOS: Flakes, Home Manager. UnFree packages, Stable branch
- systemd-boot
- iwd for WiFi
- Auto TRIM + auto GC
- CPU frequency scaling
- Plymouth + custom theme

### 🔐 Security Stack
- MAC randomization via systemd-service
- DNSCrypt-proxy2 с forced DNSSEC
- Cloudflare + NextDNS + Quad9
- Mullvad VPN with killswitch
- USB Guard with white list of devices
- SELinux + AppArmor + Firejail
- TPM2 + SecureBoot
- ClamAV + chkrootkit
- PolKit + PAM + U2F

### 💾 Storage & Backup
- BTRFS with LUKS2 encryption
- Snapper auto-snapshots every 2 hour
- Subvolumes for /, /home, /nix, /var, snapshots
- zRAM for swap

### 🖥️ Desktop Stack
- Hyprland (Wayland compositor)
- WezTerm
- NeoVim
- Zellij
- Fish Shell
- Hardware acceleration via VA-API
- Pipewire

### 🐋 Dev Stack
- Podman (rootless) for containers
- Rust nightly + cargo-* toolchain
- Python, Go, Node, Zig, Lua
- LSP + copilot everywhere
- VSCodium under firejail
- Distrobox for legacy software
