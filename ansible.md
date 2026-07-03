# Phase 2: Ansible

## Lab setup
- Control node: Ubuntu VPS #1 (this VPS)
- Managed nodes: Ubuntu VPS #2, AlmaLinux VPS, Windows 2019 VPS
- Access: Laptop (Win11) -> SSH -> Control node -> SSH/WinRM -> Managed nodes

## Day 1
- Installed ansible: sudo apt update && sudo apt install -y ansible
- Concept: agentless - no persistent software on managed nodes
- Concept: idempotency - same playbook run repeatedly = same end state
- ansible --version output:
  [paste your output here]
