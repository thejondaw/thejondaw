# DevOps Engineer

### ☁️ Infrastructure & Cloud
- AWS (VPC, EKS, Aurora, CloudWatch), Azure
- Terraform, Ansible
- NixOS, Linux (Debian, Fedora, OpenSUSE)
- QEMU/KVM, VirtualBox

### 🚀 Containers & Orchestration
- Kubernetes (RKE2/EKS/k3s), Rancher
- Docker, Podman
- Helm, ArgoCD
- NGINX Ingress
- GitOps practices

### 🔄 CI/CD & Security
- GitHub Actions
- HashiCorp Vault
- Trivy, SysDig, SonarQube
- AppArmor, iptables, SELinux
- OpenVPN, WireGuard, Mullvad
- Wireshark

### 📊 Monitoring & Backup
- Prometheus, Grafana
- Loki, Promtail
- ELK Stack
- Velero
- Veeam

### 🏆 Certifications
- CKS, CKA, CKAD
- AWS Solutions Architect Associate
- HashiCorp Terraform Associate
- LFCS
- Azure Fundamentals (AZ-900)

### 📫 Contact
- Email: aleks.safronov@proton.me
- GitHub: thejondaw
- Location: Chicago, IL

---

## My ThinkPad T14 Gen 4

🗄️ Core System

- NixOS flakes
- Linux Zen kernel
- systemd-boot
- iwd for WiFi
- Auto TRIM + auto GC
- CPU frequency scaling
- Plymouth + custom theme

🔐 Security Stack

- MAC randomization via systemd-service
- DNSCrypt-proxy2 с forced DNSSEC
- Cloudflare + NextDNS + Quad9
- Mullvad VPN with killswitch
- USB Guard with white list of devices
- SELinux + AppArmor + Firejail
- TPM2 + SecureBoot
- ClamAV + chkrootkit
- PolKit + PAM + U2F

💾 Storage & Backup

- LUKS2 encryption
- BTRFS with LUKS
- Snapper auto-snapshots every 2 hour
- Subvolumes for /, /home, /nix, /var, snapshots
- zRAM for swap

🖥️ Desktop Stack

- Hyprland (Wayland compositor)
- WezTerm
- Neovim
- Zellij
- Fish Shell
- Catppuccin Macchiato Theme
- Hardware acceleration via VA-API
- Pipewire for audio

🐋 Dev Stack

- Podman (rootless) for containers
- Rust nightly + cargo-* toolchain
- Python, Go, Node, Zig, Lua
- LSP + copilot everywhere
- VSCodium under firejail
- Distrobox for legacy software
