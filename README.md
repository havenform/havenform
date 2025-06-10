# Havenform
Havenform is a next-generation infrastructure OS purpose-built for declarative, secure-by-default Kubernetes clusters. Based on NixOS and K3s, it handles everything from Secure Boot and LUKS to GitOps bootstrap and network setup — all driven from a single user-owned seed.

🔧 Key Features
- 🧩 Seed-based key derivation (SSH, Secure Boot, LUKS, GitOps)
- 🔒 Secure Boot + LUKS from day one (TPM opt-out, Tang opt-in)
- 🖥️ SSH-in-initrd for emergency unlock or remote recovery
- ⚙️ Push or pull -based update model
- 📦 Built-in GitOps bootstrap (via FluxCD)
- 🐧 Root access included, full control with reproducible Nix
- 🌐 Optional Cilium-powered networking, ready for policy and BPF workloads
- 🧙 Minimal magic — fully declarative, fully auditable
